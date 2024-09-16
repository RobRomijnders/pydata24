# PyData 2024

This notebook accompanies the Pydata Amsterdam 2024 talk:
"Differential Privacy Made Practical"

Slides can be found at [robromijnders.nl/pydata24/slides.pdf](https://robromijnders.nl/pydata24/slides.pdf)


# Abstract
09-19, 11:20–11:55 (Europe/Amsterdam), Rembrandt
With AI becoming more common, there’s a growing need for privacy in our data processing algorithms. Differential Privacy (DP) is a popular way to quantify privacy loss and has been adopted in many applications. Examples include the Android keyboard learning about user typing, Apple’s system to collect statistics on emoticons and website usage, and the US government releasing Census population statistics. We’ll discuss in this talk an intuitive and tangible definition of differential privacy and how the above examples implement DP. In an IPython notebook, we'll demonstrate the effects of Differential Privacy on a small-scale data science problem. Additionally, I’ll refer to Python repos for doing differential privacy at scale, including for deep learning.

Differential Privacy was formalized over twenty years ago and can be interpreted as a limit on the predictive algorithm when a single data sample changes value. In summary, algorithms that satisfy DP ‘can learn from the dataset as a whole, but not from an individual sample.’ DP has building blocks to make any algorithm private, and I’ll explain these in both slides and with Python code.

Central to Differential Privacy (DP) is a critical hyperparameter that determines the level of privacy protection. Consider this: Android GBoard refines typing behaviors with an epsilon value of 8, while Apple learns about website visits with an epsilon value of 4. The talk will demystify this ‘epsilon’ parameter and illustrate its role in protecting your data from privacy attacks.


## About me
As a final-year PhD student at the University of Amsterdam, Rob Romijnders specializes in privacy-aware machine learning. Two research projects have been awarded oral talks by academic conferences such as AAAI and ICLR. Having worked at a startup and two AI companies, Rob is excited to be back at PyData and make academic topics applicable to the PyData community!

# Contact
Please reach out to me via email if you want to talk more about Differential Privacy! I'm also on the PyData2024 slack channel.