# DiTer++
* **DiTer++: Diverse Terrain and Multi-modal Dataset for Multi-Robot Navigation in Multi-session Outdoor Environments**
  	* Accepted in ICRA24 / Workshop on Future of Construction
  	
   	* Submitted to ICRA25
  	  
	<a href="https://sites.google.com/view/diter-plusplus"><img src="https://img.shields.io/badge/Project_site-link-green?logo=google&logoColor=blue&link=https%3A%2F%2Fsites.google.com%2Fview%2Fditer-plusplus"/></a>



## Download
* The dataset is provided on-demand. Link containing all data in our paper will be uploaded soon. 

## Sensor Configuration
* We configure multiple legged robot with various sensors offered in multi-session datasets.
	<p align="center"><img src=fig/sensor_setup.png /></p>
### Calibration
* Sensor calibration parameters including intrinsic & extrinsic will be uploaded soon.

## Data & Topic
* Our data are stored in rosbag format
* Each agent has custom namespace of its own to be distinguishable
* Topic name for each sensor are listed in table below
	<p align="center"><img src=fig/topic.png /></p>	

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


