# BRUTE-FORCE
Brute-forcing website login page with burpSuite
Step-by-Step Guide: Using Burp Suite for Brute Forcing website 

  

Introduction 

Brute forcing an HTTP website involves systematically attempting different combinations of usernames and passwords to gain unauthorized access. Burp Suite offers powerful tools to automate this process efficiently. This guide will walk you through the steps to set up and execute a brute force attack on an HTTP website using Burp Suite. 

   

Step 1: Configure Burp Suite 

1. Launch Burp Suite on your system. 

2. Go to the "Proxy" tab and ensure the "Intercept is on" button is toggled off. 

3. Navigate to the "Intruder" tab, where you will perform the brute force attack. 

 

  

Step 2: Import Target 

1. Open your web browser and navigate to the login page of the HTTP website. 

2. Enter any invalid username and password combination and submit the form. 

3. In Burp Suite, go to the "Proxy" tab and locate the intercepted login request. 

4. Right-click on the request and select "Send to Intruder" to import it into the Intruder tool. 

 

  

Step 3: Configure Intruder 

1. In the Intruder tab, go to the "Positions" sub-tab. 

2. Identify the parameters corresponding to the username and password fields in the login request. 

3. Highlight each parameter and click "Add §" to mark them as attack targets. 

4. Go to the "Payloads" sub-tab. 

5. Load your wordlist containing potential usernames and passwords as payloads. 

6. Configure the payload positions for the username and password fields accordingly. 

  

Step 4: Start Brute Force Attack 

1. Go to the "Options" sub-tab within the Intruder tool. 

2. Configure the attack settings, such as the number of concurrent connections and timeout values. 

3. Go back to the "Positions" sub-tab and ensure everything is set up correctly. 

4. Click on the "Start attack" button to initiate the brute force attack. 

  

Step 5: Analyze Results 

1. Monitor the progress of the brute force attack in the "Intruder" tab. 

2. As valid username/password combinations are found, they will be highlighted in the "Results" sub-tab. 

3. Review the results to identify successful login attempts and valid credentials. 

 

  

Step 6: Take Action 

1. Once valid credentials are identified, you can use them to log in to the HTTP website. 

2. Take appropriate actions based on the results of the brute force attack, such as securing accounts with stronger passwords or implementing additional security measures. 

  

Conclusion 

By following this step-by-step guide, you can leverage Burp Suite to conduct brute force attacks on HTTP websites efficiently. However, it's essential to use this knowledge responsibly and ethically, ensuring that you have proper authorization before attempting any security testing. 
