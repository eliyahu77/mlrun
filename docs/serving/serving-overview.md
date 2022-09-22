(mlrun-serving-overview)=
# Deploy models and ML applications

MLRun can produce managed real-time serverless pipelines from various tasks, including MLRun models or standard model files.
The pipelines use a real-time serverless engine, called Nuclio, which can be deployed anywhere and is capable of delivering intensive data, I/O, and compute workloads.

Serving a model begins by creating a serving function. This function can run one or more models. To load and call a model, one needs to provide a serving class. MLRun has built-in support for commonly used frameworks and therefore it is often convenient to start with {ref}`built-in classes <using_built_in_model_serving_classes>`. You can also {ref}`create your own custom model serving class<custom-model-serving-class>`. You can also find an [example notebook](../tutorial/03-model-serving.html) that shows how to build and run a serving class.

MLRun serving supports advanced real-time data processing and model serving pipelines. For more details and examples, see the {ref}`MLRun serving pipelines <serving>` documentation.

```{toctree}
:maxdepth: 1

../serving/online-model-serving-classes
../feature-store/training-serving
../serving/canary
```