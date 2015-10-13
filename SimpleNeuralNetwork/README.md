
#### 1. Basic idea for One Layer NN  
__Error__  = truth - output  
__Input__  :  1, take into account; 0 ignore   
__Factor__ = SigmoidGradient(output)  
__Adjustment__ = Error * Input * Factor
__Synaptic__ += Adjustment  

*why Sigmoid? Adjust less for extremes

#### 2. Basic idea for Two Layer NN  
define: 2 = layer2  
define: 1 = layer1

__Error2__ = truth - output2  
__Factor2__ = SigmoidGradient(Output2)  
__Delta2__ = Error2 * Factor2  
__Adjustment2__ = Output1 * Delta2  

__Error1__ = __Delta2__ * Synaptic2  
__Factor1__ = SigmoidGradient(Output1)  
__Delta1__ = Error1 * Factor1  
__Adjustment1__ = Input1 * Delta1

__Synaptic1__ += Adjustment1  
__Synaptic2__ += Adjustment2  

#### Reference:     
1.One layer NN:  
https://medium.com/technology-invention-and-more/how-to-build-a-simple-neural-network-in-9-lines-of-python-code-cc8f23647ca1  
2. Two layer NN:  
https://medium.com/technology-invention-and-more/how-to-build-a-multi-layered-neural-network-in-python-53ec3d1d326a  
3. Visual learning:  
https://medium.com/deep-learning-101/how-to-generate-a-video-of-a-neural-network-learning-in-python-62f5c520e85c  


Online python:  
https://www.pythonanywhere.com
