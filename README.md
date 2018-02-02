![VistArrow Logo](/app/src/main/res/mipmap-hdpi/ic_launcher.png)  
# Spilter  
  
#### __*An Email Spam Filter.*__  
  
  
  
### Description :ledger:    
Spliter is an Email Spam classifier allows you to classify whether a given email, x, is spam (y = 1) or non-spam (y = 0).  
It uses Support Vector Machine (SVMs) algorithm for classification.  
Spilter uses the body of the email (excluding the email headers).  
  
  
  
### How it works :question:  
Step 1: Copy & Paste your test email in emailSample.txt file  
Step 2: Run 'classifier' script in your Octave/Matlab command window.  
Step 3: Spilter takes about 1 to 2 minutes, first to train & then outputs 1 (indicating spam) or 0 (indicating non-spam).   
  
  
  
### Development  
  
Want to contribute? **:pencil:**  
  
To fix a bug or enhance an existing module, follow these steps:  
  
1. Fork the repo
2. Create a new branch (`git checkout -b exciting-stuff`)
3. Make the appropriate changes in the files
4. Add changes to reflect the changes made
5. Commit your changes (`git commit -am 'exciting-stuff!!'`)
6. Push to the branch (`git push origin exciting-stuff`)
7. Create a Pull Request  
  
  
### Interested?  
  
If you find a bug (the website couldn't handle the query and / or gave irrelevant results), kindly open an issue [here](https://github.com/thegenuinegourav/Spilter/issues/new) by including your search query and the expected result.  
  
If you'd like to request a new functionality, feel free to do so by opening an issue [here](https://github.com/thegenuinegourav/Spilter/issues/new) including some sample queries and their corresponding results.  
  
  

### How to Build
* launch Octave/Matlab
* select **Open command window**
* select the project folder
* type 'classifer' on command window  
  
  
### Articles to Learn
* https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/
* http://dataaspirant.com/2017/01/13/support-vector-machine-algorithm/
* https://gist.github.com/obstschale/7320846
* https://en.wikipedia.org/wiki/Support_vector_machine
