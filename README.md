#using efficientNet pre_model from :https://github.com/lukemelas/EfficientNet-PyTorch  
#team:  
daixiangzi:https://github.com/daixiangzi  
GGGjf  
#PRCV 2019  
农业病虫害识别     

#requirement  
pytorch-1.1.0  
cuda9.0  

#train   
python3 train.py  
#using pre_model train  
python3 pre_train.py  

#test  
python3 test.py /home/data  
output:  
data.json  
  
#Result  
accuracy:97.8%
  
#official test dataset no pulic，i only get Train dataset and Validation set. if someone is interesting in this,please contact me .
my email address: so_biu_biu@qq.com  
