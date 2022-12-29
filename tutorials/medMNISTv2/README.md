# medMNISTv2

## Notes
* Image files are encoded as unit8 which require few transformations to use `noise = torch.randn_like(x_start)`.
* Normalisation of images make them look darker
```
    if(x.min() < x.max()):  # Assuming the image isn't empty, rescale so its values run from 0 to 1
        x = (x - x.min())/(x.max() - x.min()) 
    z = x - x.mean()        # Subtract the mean value of the image
```
* Number of available images impacts on the batch size and its loss curve convergence.



