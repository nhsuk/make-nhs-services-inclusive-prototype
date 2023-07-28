# Make NHS services inclusive

## Project overview:
<p>This was initially set up as a collaborative space for teams at NHS Digital to draft guidance on how to make NHS services inclusive.</p>
<p>Many colleagues from NHS Digital (2020-2022) fed into this guidance by giving examples, critiquing or taking part in user research.</p> 
<p>Since then it has been a living document with the aim of helping NHS Digital employees to design inclusively.</p> 
<p>In March 2022 Snook were hired to design <a href="https://app.mural.co/t/snook9365/m/snook9365/1649926325095/56cdbcdd0112a86d1101e8820f1a9caa3ee4ebd7?sender=uc57e8beacae1be0dda5b2638">a roadmap for inclusive change at NHS Digital</a>. Part of their roadmap was to develop clear standards for inclusive design. Which led to them coming back in 2023 for another project to create an inclusive definition and framework for considering inclusive design at NHS England.</p>
<p>The most recent update features this definition and additional guidance that was created by Snook whilst creating the definition and framework.</p>
<p>The prototype is hosted on Heroku: https://make-nhs-services-inclusive.herokuapp.com/</p>
<p>User name and password is set via heroku in the settings tab under cofig vars.</p>

## Installation:
<ol>
<li>Open your computers version of terminal or command prompt</li> 
<li>Check if you have node by entering: <pre>node --version</pre> </li>
  
  <ol>
<li>If you have an error or a version lower than 8 then you need to download the latest version.</li>
<li>You can download and install the latest version of node here: https://nodejs.org/en/</li>
<li>Afterwards check to see if it is installed properly by entering: <pre>node --version</pre></li>
  </ol>
  
<li>Get a local version of this repo:</li>

  <ol>
<li>Navigate to the folder you want to clone the repo to in terminal <pre>cd [folder]</pre></li>
<li>Clone this repo using <pre>git clone https://github.com/nhsuk/make-nhs-services-inclusive-prototype.git</pre></li>
  </ol>
  
<li>Move into the local copy: <pre>cd [prototype-name-on-your-device]</pre></li>
<li>Install all the modules by entering: <pre>npm install</pre></li>
<li>Run it: <pre>npm run watch</pre></li>
<li>Look at it in your browser <a href="http://localhost:3000/">http://localhost:3000/</a></li>
<li>Make a branch: <pre>git checkout -b myFeature</pre></li>
<li>Make any changes you need to in your chosen code editor</li>
<li>Once you’re finished make a commit: <pre>git add .</pre>
  then
  <pre>git commit -m "new feature"</pre></li>
<li>Push your work to github: <pre>git push origin myFeature</pre></li>
<li>Merge it on github</li>
<li>This prototype has set up automatic deploys with Heroku and so once merged it will start to build your changes.</li>
<ol>
<li>You can view the Heroku dashboard here: https://dashboard.heroku.com/apps/make-nhs-services-inclusive/deploy/github</li>
<li>You can view the prototype here: https://make-nhs-services-inclusive.herokuapp.com/</li>
</ol>
<li>Switch back to main git checkout main and tidy up: <pre>git branch -D myFeature</pre></li>
</ol>
