<div align="center">
  <h1>DiTer++ Datasets</h1>
  <a href="https://sites.google.com/view/diter-plusplus"><img src="https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg" alt="Project" /></a>
  <a href="https://youtu.be/RJ_netgAOT8"><img src="https://badges.aleen42.com/src/youtube.svg" alt="YouTube" /></a>
  <br />
  <br />
  
**(Under Review) [IEEE ICRA 25]** This repository is the official code for DiTer++: Diverse Terrain and Multi-modal Dataset for Multi-Robot Navigation in Multi-session Outdoor Environments.

  <a href="https://scholar.google.com/citations?user=2bvLmqQAAAAJ&hl=ko" target="_blank">Juwon Kim</a><sup></sup>,
  <a href="https://scholar.google.com/citations?user=t5UEbooAAAAJ&hl=ko" target="_blank">Hogyun Kim</a><sup></sup>,
  <a href="https://scholar.google.com/citations?user=ZAO6skQAAAAJ&hl=ko" target="_blank">Seokhwan Jeong</a><sup></sup>,
  <a href="https://scholar.google.com/citations?user=gGfBRawAAAAJ&hl=ko" target="_blank">Youngsik Shin</a><sup></sup>,
  <a href="https://scholar.google.com/citations?user=W5MOKWIAAAAJ&hl=ko" target="_blank">Younggun Cho</a><sup>†</sup>

**[Spatial AI and Robotics Lab (SPARO)](https://sites.google.com/view/sparo/%ED%99%88?authuser=0&pli=1)**
  
</div>

## News
* Accepted in ICRA24 / Workshop on Future of Construction
* Submitted to ICRA25


## Download
* The dataset is provided on-demand. Link containing all data in our paper will be uploaded soon. 

## Sensor Configuration
* We configure multiple legged robot with various sensors offered in multi-session datasets.
	<p align="center"><img src=fig/sensor_setup.png/></p>
### Calibration
* Sensor calibration parameters including intrinsic & extrinsic will be uploaded soon.

## Data & Topic
* Our data are stored in rosbag format
* Each agent has custom namespace of its own to be distinguishable
* Topic name for each sensor are listed in table below
	<p align="center"><img src=fig/topics.png /></p>	

## Example Sequence in each sequence
* Our perceptual sensor data from each robot with heterogenous LiDAR.
	<p align="center"><img src=fig/lawn_small.gif /></p>
* Multi-session sensor data is also avaliable from each site.
	<p align="center"><img src=fig/park_multi_session.gif /></p>

## Map
* The global map is generated using [Point-LIO](https://github.com/hku-mars/Point-LIO), and [Uni-Mapper](https://sites.google.com/view/sparo/activities/icra-2024#h.wmpj5r2atjjp).  
<p align="center"><img src=fig/glob_map.png /></p>

## Cite DiTer++
<pre>
<code>
@article{kim2024diter,
  title={DiTer++: Diverse Terrain and Multi-modal Dataset for Multi-Robot Navigation in Multi-session Outdoor Environments},
  author={Kim, Juwon, Jeong, Seokhwan and Kim, Hogyun and Cho, Younggun}
}
</code>
</pre>  

## Contact
* **Juwon Kim (lambertkim317@gmail.com)**
* **Seokhwan Jeong (eric5709@inha.edu)**
* **Hogyun Kim (hg.kim@inha.edu)**


