<div align="center">
  <p>
    <a align="center" href="" target="_blank">
      <img
        width="850"
        src="URL OF BANNER ART FOR CHANNEL"
      >
    </a>
  </p>
  <br>

</div>
#

These scripts are used to remove objects in videos. Run in them in sequence and checkout the video below from my youtube channel to see how they work.

## Scripts in order they should run (top - 1st)
| **notebook** | **open in colab** | **complementary materials** |
|:------------:|:-------------------------------------------------:|:---------------------------:|
| [Convert Video To images](https://github.com/g-make-it/AI_Video_Removal/blob/main/saving_images_of_frame_to_gdrive.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/g-make-it/AI_Video_Removal/blob/main/saving_images_of_frame_to_gdrive.ipynb)  [![YouTube](https://badges.aleen42.com/src/youtube.svg)](https://youtu.be/VUA8uE51z1s) | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/g-make-it/AI_Video_Removal)|
| [Generate Mask - using SAM/GroundingDino](https://github.com/g-make-it/AI_Video_Removal/blob/main/generate_and_saving_masks_to_drive.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/g-make-it/AI_Video_Removal/blob/main/generate_and_saving_masks_to_drive.ipynb)  [![YouTube](https://badges.aleen42.com/src/youtube.svg)](https://youtu.be/VUA8uE51z1s) | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/IDEA-Research/Grounded-Segment-Anything)|
| [Remove Object and Create Video (using mask)](https://github.com/g-make-it/AI_Video_Removal/blob/main/removing_items_from_videos_by_using_object_guided_flow_transfomers_removal.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/g-make-it/AI_Video_Removal/blob/main/removing_items_from_videos_by_using_object_guided_flow_transfomers_removal.ipynb)  [![YouTube](https://badges.aleen42.com/src/youtube.svg)](https://youtu.be/VUA8uE51z1s) | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/hitachinsk/FGT) [![arXiv](https://img.shields.io/badge/arXiv-2304.02643-b31b1b.svg)](https://arxiv.org/abs/2208.06768)|
| [Remove Flickering and Recreate Video](https://github.com/g-make-it/AI_Video_Removal/blob/main/convert_clean_video_to_images_and_remove_flickering.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/g-make-it/AI_Video_Removal/blob/main/convert_clean_video_to_images_and_remove_flickering.ipynb)  [![YouTube](https://badges.aleen42.com/src/youtube.svg)](https://youtu.be/VUA8uE51z1s) | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/g-make-it/AI_Video_Removal) |


## 🎬 videos

[Subscribe](https://www.youtube.com/@g-program-it), and stay up to date with our latest YouTube videos!

<p align="center">
    <a href="https://youtu.be/VUA8uE51z1s">
        <img src="URL of image" alt="AI Video Editing">
    </a>
</p>

## 💻 run locally

locally, below you will find instructions on how to do it. Remember don't install your dependencies globally, use
[venv](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/).

```console
# clone repository and navigate to root directory
git clone git@github.com:roboflow-ai/notebooks.git
cd notebooks

# setup python environment and activate it
python3 -m venv venv
source venv/bin/activate

# install and run jupyter notebook
pip install notebook
jupyter notebook
```


