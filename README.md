<h4> object-detection </h4>
<p>use the tensorflow object detection api, for the model starting to train 100 images with trn_size: around 90 images and test_size: around images</p>
the accuracy is on the way for improving
- Traine the model on the AWS P3 instance for 15k steps within 1 hour and the loss is below the range of 0.8-0.9. 

Transfer the XML file to POSCAL VOC file and get model runs on the fastai framework based on object detection methods, get stuck on 
`ValueError: Expected more than 1 value per channel when training, got input size torch.Size([1, 1024])` 


Resource: 
-annotation tool: 
<ul>
  <li>https://github.com/tzutalin/labelImg</li>
  <li>https://github.com/wkentaro/labelme</li> 
</ul>
http://openaccess.thecvf.com/content_ECCV_2018/papers/NIKITA_DVORNIK_Modeling_Visual_Context_ECCV_2018_paper.pdf
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md   
