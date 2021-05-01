# MSBA6330-Road-Speed-ID
Demonstration of Road and Speed Identification from Satellite Images on AWS Sagemaker  

*This project repository is created in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.*

**Project Team: Callie Page, Mark Chen, Weizhong Yao, Laura Catano**

Video:  
Flyer: 

## Project Summary  
Satellite images are a rich data source that provide a lot of business value, although they are usually complex and expensive to process. Sagemaker provides a quick solution for building and training machine learning models on massive satellite image data. We will be showing an example of classifying roads found in satellite images for navigation software using AWS services including Sagemaker and S3. In this project, we will explain the workflow of Sagemaker, show an end-to-end demo, and introduce the business values brought by this technique. 

## Setup Instructions
**Create an AWS Sagemaker On-Demand Notebook Instance**  
The recommended instance size is at lease ml.t3.large to try out the code, although ml.m5.12xlarge is preferrable due to the amount of memory required to predict outputs for many images. If you would like to train your own version of the roadway and speed detection model, a GPU-enabled instance like a ml.p3.8xlarge is required. The satellite image dataset is very large, so the volume size of the instance should be at lest 60GB.

**Clone the Repository**  
After the instance is started, launch Jupyter Lab and then open a new terminal. Run the following commands to access a copy of the code and dependencies:

```
$ cd SageMaker
$ git clone https://github.com/calliepage/MSBA6330-Road-Speed-ID
$ cd MSBA6330-Road-Speed_ID
```

Then, open the notebook Roadway_Speed_Identification.ipynb and follow the embedded instructions.

## Additional Resources
