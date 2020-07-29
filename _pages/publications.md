---
layout: page
title: Publications
permalink: /publications/
---
<style type="text/css">
	ul li {
		padding-bottom: 10px;
	}

	.content {
	  padding: 0 18px;
	  display: none;
	  overflow: hidden;
	  background-color: white;
	  font-family: Liberation Mono;
	  font-size: 14px;
	}

	.explanation {
	  background-color: white; /* Green */
	  border: none;
	  color: black;
	  padding: 6px 6px;
	  text-align: center;
	  text-decoration: none;
	  display: inline-block;
	  font-size: 16px;
	  margin: 4px 2px;
	  transition-duration: 0.4s;
	  cursor: pointer;
	}

	.explanation:hover {
	  background-color: #008CBA;
	  color: white;
	}
</style>

<h1> 2020 </h1>
<ul>
	<li>
	  Gao, Ruihan; Taunyazov, Tasbolat; Lin, Zhiping; Wu, Yan. 
	  <b>Supervised Autoencoder Joint Learning on Heterogeneous Tactile Sensory Data: Improving Material Classification Performance.</b>
	  2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), IEEE, Las Vegas, USA <br>
	  <i>Accepted, Pdf is coming soon.</i>
	  <a href="https://github.com/dexrob/Supervised-Autoencoder-Joint-Learning-on-Heterogeneous-Tactile-Sensory-Data.git">Code</a>&nbsp;<a href="https://github.com/dexrob/BioTac_slide_20_50.git">Data</a> 
	</li>
	<li>
		 Taunyazov, Tasbolat; Chua, Yansong; Gao, Ruihan; Soh, Harold; Wu, Yan.
		 <b>Fast Texture Classification Using Tactile Neural Coding and Spiking Neural Network. </b>
		 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), IEEE, Las Vegas, USA.
		 <i>Accepted, Pdf is coming soon.</i>
		 <a href="https://github.com/dexrob/fast_texture_recognition.git">Code</a>&nbsp;<a href="https://github.com/dexrob/tactile_data_IROS2020_preprocessed.git">Data</a> 

	</li>
</ul>
<h1> 2019 </h1>
<ul>
	<li>
	 Taunyazov, Tasbolat; Koh, Hui Fang; Wu, Yan; Cai, Caixia; Soh, Harold. <br>
	 <b>Towards effectiv
	 e tactile identification of textures using a hybrid touch approach.</b> <br>
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
	 <br>
	  <button onclick="document.location='../texture_classification_icra_2019/index.html'" class="explanation">Explain more ...</button> 
	</li>
</ul>

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