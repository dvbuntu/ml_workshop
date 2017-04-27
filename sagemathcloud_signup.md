# SageMathCloud

[SageMathCloud](cloud.sagemath.org) is an online service to do computations in a remote Jupyter notebook.  This course will be using the free tier to demonstrate data science, computing, and machine learning using Python with supporting libraries like NumPy, Matplotlib, and TensorFlow.  Because everything is online, you don't need to install anything locally.

## Signup

While SageMathCloud is free, you do need to sign up for an account.  Go to [http://cloud.sagemath.org] to get started.  If you want, you can sign up with an existing Facebook, GitHub, Google, or Twitter account.  But that's optional, you can just create a free account with whatever email you you like.  Click the green "Sign Up" button to get started.

## Setup

Because everything is online and comes with preconfigured setups for typical computing, this is pretty easy.  Click the "Create a new project" button (or go to the "Projects" tab in the upper left if you don't see that) and give it any name you like.  It starts empty, a blank slate to get started on.  If you prefer to copy and paste or read code, download the class notes from [GitHub](raw.githubusercontent.com/dvbuntu/ml_workshop/master/ml_workshop.ipynb) and upload them as a new file.  To code along live with the lecture, simply click the `+ New` in the upper left of the project page.  You can name it whatever you want, but you should select `Jupyter Notebook` as the type.

After it loads, click the tab called "kernel" just below the name of the notebook.  Change this to "Python 3 (Anaconda)".  Anaconda is a Python distribution that comes prepackaged with a significant number of computing packages and machine learning tools.  While it's put together by a for-profit company, Continuum Analytics, they do make it freely available.  You're now ready to start doing data science in SageMathCloud!

If you prefer to roll your own setup, you'll need to install Python (2 or 3), Jupyter notebook, NumPy, matplotlib, scikit-learn, and TensorFlow.  Anaconda Python will take care of most of these, but I can't guarantee how uptodate they are. 

## Free vs Paid Tiers

Loading a new project might take awhile.  Because SageMathCloud is provided as a free service (with no ads even), you're at the mercy of available computing power (and generally limited in how much computing you can do).  If you want to make sure you have compute resources, you can choose to upgrade to one of their paid tiers (following any one of a numerous reminders and links on their website).  You'll find their pricing is more expensive than say Google Compute Engine or Amazon Web Services, but you don't have to do any of the system management or configuration.  I recommend sticking with the free tier while you're learning.

If you have a computer with a powerful graphics card at the office or home (as for video gaming), you can likely use it for most of your computing projects.  Unless you truly have huge amounts of data and need for massively parallel operations, a consumer grade Graphics Processing Unit (GPU) with modest computer specs will take you far.
