# 100 Days Of Code - Log


## Day 0: October 26, 2020

![rocket take off](https://media.giphy.com/media/tXLpxypfSXvUc/giphy.gif)

**Today's Progress**: Simple website sketches and initial project set up.

**Thoughts:** Starting from scratch on a old project that I completed at the beginning of a course I took. I cringe at the how it looks and operates, it relies on old Javascript and HTML. Here are some of the sketches for the site. I decided to work with the MERN stack and use Tailwind as the css framework. It took a bit to figure out the scripts. 

Used this link as a reference to set up the front end: [https://daveceddia.com/tailwind-create-react-app/](https://daveceddia.com/tailwind-create-react-app/)

<br/>

#### Sketch of advanced search
![sketch of advanced search](/imgs/day0/Day0-1.png)
#### Sketch of potential models
![Models](/imgs/day0/Day0-2.png)
#### Sketch of potential splash/landing
![Models](/imgs/day0/Day0-3.png)


**Link to work:** [Repo link](https://github.com/Beki-G/all-my-shiki)



<hr/>
<br />

## Day 1: October 27, 2020

**Today's Progress**: Worked on the Models and sketches a bit more. These models might change again as I build the back end to make the relationships work. Probs will need to gather a large amt of data from in game (or at least a sizable sample to build the back end). Some of that information is already online. And while I'm not found of spiders it led me down a rabbit hole on web crawling. Might turn into a sideroute worth checking out. 

![](https://media.giphy.com/media/zpjpvAGOM36bm/giphy.gif)

**Link to work:** [Repo](https://github.com/Beki-G/all-my-shiki)

<hr/>
<br />

## Day 2: October 29, 2020
**Today's Progress**: Felt sick yesterday, but was back at it today.<br />
![](/imgs/day2/day2.gif) <br />
 Made significant some progress on the landing page. Here's what I accomplished:
* Made Hero Section to go on the home page
* Add a dynamic dropdown that uses API to make the options, Used useEffect & useState;
* Wrote a script to import data into database. I used a chrome extention to export data from google sheets to a JSON/JS file and wrote the script to import that large file. 
* Learned about SVG and wrote a hero section component (was gonna use this for the Splash hero but decided not to)

#### Current Homepage
![current homepage progress](/imgs/day2/Day2-1.png)

**Thoughts**: I would like to learn more about SVG there a lot more to it and I could see my self incorporating it more in the future. 



**Link to work:** [Repo](https://github.com/Beki-G/all-my-shiki)

<hr/>
<br />

## Day 3: October 30, 2020

**Today's Progress**: Powered thorough another day :smile: <br />

There was another good chunk that I had to read through/try to get some of the following to work:

* Add/modify routes & scripts to arrange data in DB.
* Add conditional rendering of a component

**Thoughts**: Conditional rendering is a little tricky once you want to change the data in it. Had to set a state on a parent and then send the data down to the component. Originally I had the data for the tags as a dump straight into MongoDB, then I realized that the casing on names had to be changed. Wrote the script to change casing. 

#### Current Homepage
![current homepage progress](/imgs/day3/Day3-1.png)

**Link to work:** [Repo](https://github.com/Beki-G/all-my-shiki)