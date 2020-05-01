# MURA  bone X-rays
## Networks (Results)
> To beat : kappa 0.843

- pretrained resnet34 + adamW + weight decay + mixup + oevrsampling
    - kappa : 56.8% (not much training)
- pretrained resnet34 + adamW + weight decay + progressive resizing (64-> 128->256->128)
    - kappa : 64.7% 
- xresnet34 (not pretrained)+ adamW + weight decay + progressive resizing (64-> 128->256->128)
    - kappa : 66.9 %
    - wayy faster without pre trained
- pretrained densenet + adamW + weight decay + progressive resizing (128->256->128)
    - kappa :  %
    

## Conclusion
- mixup and over sampling isnt always useful so dont use it all the time
- xresnet >>> resnet