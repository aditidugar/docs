---
title: Learning pipelines
description: Learn how to build learning pipelines in ML.NET.
ms.date: 06/01/2018
author: aditidugar
ms.author: johalex
ms.topic: conceptual
ms.prod: dotnet-ml
ms.devlang: dotnet
manager: wpickett
---
# Learning pipelines

> [!NOTE]
> This topic refers to ML.NET, which is currently in Preview, and material may be subject to change. For more information, visit the ML.NET introduction.

Learning pipelines in ML.NET combine data loading, feature engineering, and modeling into a single pipeline. Your trained model then uses this pipeline to ensure that the same operations are applied when making your prediction. You can build a learning pipeline with the ML.NET API in five easy steps. Click on each to learn more.

1. [Create a learning pipeline](#create-a-learning-pipeline)
2. [Load your data](#load-your-data)
3. [Transform your data](#transform-your-data)
4. [Fit your model](#fit-your-model)
5. [Train your model](#train-your-model)

> [!NOTE]
> You must apply these steps in order to successfully execute your pipeline.

## Create a learning pipeline

The first step in the process is to create a new learning pipeline. For this example, say you are creating a pipeline called "myLearningPipeline". Using the `LearningPipeline` class, you can easily do this by writing the following code:

```csharp
var myLearningPipeline = new LearningPipeline();
```

## Load your data

Next, you must load your data into the pipeline you have created using the `TextLoader` class. The `TextLoader` can handle a variety of data sources such as text files (.csv, .tsv), parquet, and more. It can even process file sets. You can implement data loading by writing 

## Transform your data


## Fit your model


## Train your model


## Next steps

After building your pipeline and training your model, you can 