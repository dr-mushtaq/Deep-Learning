
# Introduction 

There’s been a lot of hype about neural networks. And perhaps some of that hype is justified, given how well they’re working. But it turns out that so far, almost all the economic value created by neural networks has been through one type of machine learning, called supervised learning. Let’s see what that means, and let’s go over some examples.


## 📑 Table of Contents  

- [Software Categories](#Software-Categories)  
- [What is meant by programming](#1-What-is-meant-by-programming)  


# **Supervised Learning example of Neural network**

In supervised learning, you have some input x, and you want to learn a function mapping to some output y. So for example, just now we saw the housing price prediction application where you input some features of a home and try to output or estimate the price y. Here are some other examples that neural networks have been applied to very effectively.

Possibly the single most lucrative application of deep learning today is online advertising, maybe not the most inspiring, but certainly very lucrative, in which, by inputting information about an ad to the website it’s thinking of showing you, and some information about the user, neural networks have gotten very good at predicting whether or not you click on an ad. And by showing you and showing users the ads that you are most likely to click on, this has been an incredibly lucrative application of neural networks at multiple companies. Because the ability to show you ads that you’re more likely to click on has a direct impact on the bottom line of some of the very large online advertising companies.

Computer vision has also made huge strides in the last several years, mostly due to deep learning. So you might input an image and want to output an index, say from 1 to 1,000 trying to tell you if this picture, it might be any one of, say a 1000 different images. So, you might us that for photo tagging.

I think the recent progress in speech recognition has also been very exciting, where you can now input an audio clip to a neural network, and have it output a text transcript.

Machine translation has also made huge strides thanks to deep learning where now you can have a neural network input an English sentence and directly output say, a Chinese sentence.

And in autonomous driving, you might input an image, say a picture of what’s in front of your car as well as some information from a radar, and based on that, maybe a neural network can be trained to tell you the position of the other cars on the road. So this becomes a key component in autonomous driving systems.

## **1. Virtual environments in Anaconda**
   
What is it: A virtual environment is like a “workspace” where you can install a set of packages with specific versions. These environments are isolated from each other and from the base environment of your system.

So, why use virtual environments at all [3]?

- Primary reason for using virtual environments lies in managing dependencies and avoiding conflicts between packages.
- Different packages can have conflicting requirements for their dependencies, meaning installing one may cause the other to stop working.
- If you put them in separate environments instead, you can switch between the environments as needed, and both will continue to work.
- This enhances project stability and reproducibility, as you can rest assured that each project’s dependencies are contained and managed separately

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/c483df44-3523-425b-815d-c3a02bbb8db5_700x286.png"></a>
</p>

Thus by using environments, you won’t breaking existing projects when you install, update, or remove packages, since each project can have its own environment.
You can also delete environments once you’re done with them, and if you run into problems with an environment, it’s easy to start a new one!
In Short, virtual environments serve as invaluable tools for managing dependencies, resolving conflicts, and maintaining project isolation in Python development.
By leveraging virtual environments, you can ensure project stability, streamline package management, and enhance productivity in your coding endeavors.

# **Installing Anaconda**

1- Visit the official Anaconda Website: www.anaconda.com

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/b4f1862a-eb6b-4387-8bdc-72c81c248aed_700x249.png"></a>
</p>

-  Provide your email to download distribution
- It will send a link to your Email.
-  Click on Download Now.
-  It will redirect you the Anaconda Download Webpage.

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/21c15efc-5f93-4cf1-997b-f3fdc58cd6fc_700x309.png"></a>
</p>

- Click on Download to get download started
- It will take some time to download as the Anaconda File Size is pretty large.
-  After Downloading, Run the Installer

  
<p align="center">
<img src=" https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/image.jpg"></a>
</p>

> Keep all settings to Default.
<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/image%20(1).jpg"></a>
</p>


# Installing Visual Studio Code:

> Navigate to the official Visual Studio Code website.

[Download](https://code.visualstudio.com/?source=post_page-----b353db76165d---------------------------------------)

> Run Installer: Once the download is complete, run the installer and follow the on-screen prompts to install Visual Studio Code.
> When installing Visual Studio Code (VSC), you can keep all the default settings.

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/image%20(2).jpg"></a>
</p>

# Python Setup in VS Code

Setting up the Python extension in Visual Studio Code (VS Code) is a straightforward process. Here’s a step-by-step guide to help you get started:

>Open Visual Studio Code

> Click on the Extensions view icon on the Sidebar (or press Ctrl+Shift+X), then search for "Python" in the Extensions Marketplace.

>The official Python extension should appear at the top of the search results. Click the “Install” button next to it to install the extension.

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/08643b60-3ec0-4f7a-821f-b5a227c49658_700x177.png"></a>
</p>

Open Vscode> Extension>Python(intellisense)

# Setup Interpreter VS Code using Anaconda

> Open VS Code

> Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS) to open the Command Palette.

> open user setting

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/b49ff646-aade-4d85-a040-ff05b4eecd04_700x110.png"></a>
</p>

> Search Python Path

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/2427fea9-a17b-4eff-81b9-004cdcf1911f_700x146.png"></a>
</p>
Alternative Method:

<p align="center">
<img src="https://github.com/dr-mushtaq/Python-Notes/blob/master/Python/2e5d1857-ea45-432e-bab7-12d4e3e40f37_700x237.png"></a>
</p>

Ø If the selected Anaconda environment is not automatically activated, you might need to activate it manually. You can do this by opening a terminal in VS Code (`Ctrl+``) and running:

With the Anaconda interpreter set up in Visual Studio Code, you’re ready to start coding in Python! Write your Python code in the editor, and use the various features provided by the Python extension for code editing, debugging, and more.

That’s it! You’ve successfully set up the Python interpreter in Visual Studio Code using Anaconda. Now you can seamlessly develop Python projects within the Anaconda environment using the powerful features of VS Code

# Installing Python in VS Code Manually

Here’s a guide on how to manually install Python in Visual Studio Code (VS Code)

Step 1: Install Python

Download Python: Visit the official Python website and download the latest version suitable for your operating system (Windows, macOS, or Linux).

Download Python
The official home of the Python Programming Language
www.python.org

Ø Choose your Python Version and Opening System and click on Download Link to Start downloading the Python Installer File.



Run the Installer: Open the downloaded file to start the installation.Ø Once download is complete, run the python installer.

For Windows users, ensure you check the box that says “Add Python to PATH” — this will allow you to run Python from any terminal without configuring paths manually.

On macOS or Linux, Python might come pre-installed, but updating to the latest version is recommended.



Ø Proceed with the installation by clicking “Install” or “Next.” The installer will then copy the necessary files and configure Python on your system. This process may take a few minutes to complete.

Configure the Python Interpreter

Select Python Interpreter:

Open a Python file or create a new one (.py extension).

Ctrl+Shipt+P > Select Interpreter


Ø Congratulations! You’ve successfully installed Python on your system. You can now start using Python for coding, scripting, or running Python programs.

# References
[How to Configure Visual Studio Code and Anaconda for Python Programming](https://mushtaqmsit.substack.com/p/how-to-configure-visual-studio-code)


































































