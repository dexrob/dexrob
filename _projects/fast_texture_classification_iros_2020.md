---
exclude: true
layout: publications
title: Fast Texture Classification Using Tactile Neural Coding and \\ Spiking Neural Network
permalink: /fast_texture_classification_iros_2020/
---

<style type="text/css">
	.content {
	  padding: 0 18px;
	  display: none;
	  overflow: hidden;
	  background-color: white;
	  font-family: Liberation Mono;
	  font-size: 14px;
	}
</style>

Touch is arguably the most important sensing modality in physical interactions. However, tactile sensing has been largely under-explored in robot applications owing to the complexity in making perceptual inferences until the recent advancements in machine learning or deep learning in particular. Touch perception is strongly influenced by both its temporal dimension similar to audition and its spatial dimension similar to vision. While spatial cues can be learned episodically, temporal cues compete against the system’s response/reaction time to provide accurate inferences. <br>
<img src='../assets/imgs/SNN_IROS/example2.png'>
<tag style="font-size:14px">Fig. 1. An exmple of threshold encoding on tactile data</tag>
<br>

In this paper, we propose a fast tactile-based texture classification framework which makes use of the spiking neural network to learn from the neural coding of the conventional tactile sensor measurements. The framework is implemented and tested on two independent tactile datasets collected in sliding motion on 20 material textures. Our results show that the framework is able to make much more accurate inferences ahead of time as compared to that by the state-of-the-art learning approaches.
<img src='../assets/imgs/SNN_IROS/clustering_with_material.png'>
<tag style="font-size:14px">Fig. 2. t-SNE on encoded spike trains</tag>
<br>



<hr style="width:100%;text-align:left;margin-left:0;margin-top: 20px;margin-bottom: 20px;">

<i>For more info, please read the following article:</i>
<b>The paper is accepted. The pdf link is coming on the way :) </b>
<a href="https://github.com/dexrob/fast_texture_recognition.git">Code</a>&nbsp;<a href="https://github.com/dexrob/tactile_data_IROS2020_preprocessed.git">Data</a> 

<!-- Note: Change the citation info later, once the pdf is ready, -->
<!-- <ul>
	<li>
		Taunyazov, Tasbolat; Koh, Hui Fang; Wu, Yan; Cai, Caixia; Soh, Harold. <br>
		<b>Towards effective tactile identification of textures using a hybrid touch approach.</b> <br>
		2019 International Conference on Robotics and Automation (ICRA), pp. 4269-4275, IEEE, Montreal, Canada, 2019, ISBN: 978-1-5386-6027-0.<br>
		<a href="https://www.yan-wu.com/docs/taunyanov2019towards.pdf">Pdf</a> &nbsp; <a href="">Data</a> &nbsp;<a class="collapsible">Cite</a>
		<div class="content">
		<br>
		@inproceedings{taunyazov2019towards, <br>
		  title={Towards effective tactile identification of textures using a hybrid touch approach},<br>
		  author={Taunyazov, Tasbolat and Koh, Hui Fang and Wu, Yan and Cai, Caixia and Soh, Harold},<br>
		  booktitle={2019 International Conference on Robotics and Automation (ICRA)},<br>
		  pages={4269--4275},<br>
		  year={2019},<br>
		  organization={IEEE}<br>
		}
		</div>
	</li>
</ul> -->

<script>
var coll = document.getElementsByClassName("collapsible");
var i;
for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>