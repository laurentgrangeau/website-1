# V1beta1PredictorConfig

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**default_gpu_image_version** | **str** | default predictor docker image version on gpu | 
**default_image_version** | **str** | default predictor docker image version on cpu | 
**default_timeout** | **str** | Default timeout of predictor for serving a request, in seconds | [optional] 
**image** | **str** | predictor docker image name | 
**multi_model_server** | **bool** | Flag to determine if multi-model serving is supported | [optional] 
**supported_frameworks** | **list[str]** | frameworks the model agent is able to run | 

[[Back to Model list]](../sdk_doc.md#documentation-for-models) [[Back to API list]](../sdk_doc.md#documentation-for-api-endpoints) [[Back to README]](../sdk_doc.md)


