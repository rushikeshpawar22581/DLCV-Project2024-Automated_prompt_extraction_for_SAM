# DLCV-Project : Weakly Supervised automated extraction of optimal visual prompts for foundational models in medical image segmentation 
Name : Rushikesh Pawar & Vivek Dhamale

Abstract: The lack of publicly available quality annotations in medical imaging has been the bottleneck for training 
large-scale deep learning models for medical image segmentation, due to the time-consuming nature of 
the task. Vision foundation models, often trained on large-scale visual images of various modalities, could serve as 
the basis for building medical segmentation applications. Promptable vision foundational models like SAM (Segment Anything Model, developed by Meta) is 
pretrained on natural images to return valid segmentation mask for a relevant prompt, (e.g.,
foreground/background points, a rough box or mask, freeform text, or, even text, indicating the regions 
to segment in an image). However, SAMs typically involve providing manual prompts. In this paper we propose a method to automatically extract optimal prompts for SAM is a weakly supervised manner.
We also evaluate the performance of different prompts (point,bounding box and their combination) on the task of medical image segmentation.
We compare the quality of automatically extracted prompts with manually provided prompts on the basis of how well they perform on medical image segmentation task.
