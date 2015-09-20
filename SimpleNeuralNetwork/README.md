
#### Basic idea for One Layer NN  
_Error_  = truth - output  
_Input_  :  1, take into account; 0 ignore   
_Factor_ = SigmoidGradient(output)  
_Adjustment_ = Error * Input * Factor
_Synaptic_ += Adjustment  

*why Sigmoid? Adjust less for extremes


Reference:     
1.One layer NN:  
https://medium.com/technology-invention-and-more/how-to-build-a-simple-neural-network-in-9-lines-of-python-code-cc8f23647ca1  
2. Two layer NN:  
https://medium.com/technology-invention-and-more/how-to-build-a-multi-layered-neural-network-in-python-53ec3d1d326a  
3. Visual learning:  
https://medium.com/deep-learning-101/how-to-generate-a-video-of-a-neural-network-learning-in-python-62f5c520e85c  


Online python:  
https://www.pythonanywhere.com
