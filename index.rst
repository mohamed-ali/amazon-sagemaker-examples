.. image:: _static/sagemaker_gears.jpg
  :width: 600
  :alt: sagemaker_logo

Amazon SageMaker Example Notebooks
==================================

.. image:: https://readthedocs.org/projects/sagemaker-examples-test-website/badge/?version=latest

Welcome to Amazon SageMaker.
This site highlights example Jupyter notebooks for a variety of machine learning use cases that you can run in SageMaker.

This site is based on the `SageMaker Examples repository <https://github.com/aws/amazon-sagemaker-examples>`_ on GitHub.
To run these notebooks, you will need a SageMaker Notebook Instance or SageMaker Studio.
Refer to the SageMaker developer guide's `Get Started <https://docs.aws.amazon.com/sagemaker/latest/dg/gs.html>`_ page to get one of these set up.

On a Notebook Instance, the examples are pre-installed and available from the examples menu item in JupyterLab.
On SageMaker Studio, you will need to open a terminal, go to your home folder, then clone the repo with the following::

   git clone https://github.com/aws/amazon-sagemaker-examples.git


.. toctree::
  :maxdepth: 1

  intro.rst


.. toctree::
   :maxdepth: 1
   :caption: SageMaker Studio

   aws_sagemaker_studio/index
   sagemaker-lineage/index


.. toctree::
   :maxdepth: 1
   :caption: SageMaker End-to-End Examples

   end_to_end/fraud_detection/index
   end_to_end/music_recommendation/index
   end_to_end/nlp_mlops_company_sentiment/index

.. toctree::
    :maxdepth: 1
    :caption: Patterns

    patterns/ml_gateway/index


.. toctree::
    :maxdepth: 1
    :caption: SageMaker Use Cases

    use-cases/index


.. toctree::
   :maxdepth: 1
   :caption: Autopilot

   autopilot/index


.. toctree::
   :maxdepth: 1
   :caption: Ingest Data

   ingest_data/index


.. toctree::
   :maxdepth: 1
   :caption: Label Data

   label_data/index


.. toctree::
   :maxdepth: 1
   :caption: Prep Data

   prep_data/index


.. toctree::
   :maxdepth: 1
   :caption: Feature Store

   sagemaker-featurestore/index


.. toctree::
   :maxdepth: 1
   :caption: Frameworks

   training/frameworks


.. toctree::
   :maxdepth: 1
   :caption: Training

   training/algorithms
   reinforcement_learning/index
   sagemaker-experiments/index
   sagemaker-debugger/index
   training/tuning
   training/distributed_training/index
   sagemaker-training-compiler/index
   sagemaker-script-mode/index
   training/bring_your_own_container
   training/management


.. toctree::
   :maxdepth: 1
   :caption: Inference

   inference/index


.. toctree::
   :maxdepth: 1
   :caption: Workflows

   sagemaker-pipelines/index
   sagemaker_processing/index
   sagemaker-spark/index
   step-functions-data-science-sdk/index


.. toctree::
   :maxdepth: 1
   :caption: Advanced examples

   sagemaker-clarify/index
   scientific_details_of_algorithms/index
   aws_marketplace/index


.. toctree::
   :maxdepth: 1
   :caption: Community examples

   contrib/index
