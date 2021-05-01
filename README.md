# MSBA6330-Road-Speed-ID
Demonstration of Road and Speed Identification from Satellite Images on AWS Sagemaker  

*This project repository is created in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.*

**Project Team: Callie Page, Mark Chen, Weizhong Yao, Laura Catano**

Video:  
Flyer: 

## Project Summary

## Setup Instructions
**Create an AWS Sagemaker On-Demand Notebook Instance**  
The recommended instance size is at lease ml.t3.large to try out the code. If you would like to train your own version of the model, a GPU-enabled instance like a ml.p3.8xlarge is required. The satellite image dataset is very large, so the volume size of the instance should be at lest 60GB.

**Clone the Repository**
After the instance is started, launch Jupyter Lab and then open a new terminal. Run the following commands to access a copy of the code and dependencies:

```
$ cd SageMaker
$ git clone https://github.com/calliepage/MSBA6330-Road-Speed-ID
$ cd MSBA6330-Road-Speed_ID
```

Then, open the notebook Roadway_Speed_Identification.ipynb and follow the embedded instructions.

## Additional Resources
