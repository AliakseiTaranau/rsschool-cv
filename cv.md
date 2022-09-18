# Aliaksei Taranau
## Contact Information:
* __Phone:__ +48-508-491-627
* __E-mail:__ aleksei.taranov@gmail.com
* __Telegram:__ Aliaksei_TaranaU
* [__LinkedIn__](https://www.linkedin.com/in/aliaksei-taranau-34a36722b/)
***
## About Myself:
I am beginner full stack developer searching for first employment.

I have recently completed a full stack developer bootcamp course and am currently looking for a vacancy that would allow me to continue my professional development.


I speak Polish, Russian, Belarusian English. I am extremely motivated and most eager to learn new and improve my existing skills.
***
## Skills:
* HTML5, CSS3
* JavaScript/React
* Git, GitHub
* Python/Django
***
## Code Example:
__Silly story generator from MDN Web Docs:__ The description of the task can be found at this [link](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Silly_story_generator), below is the decision code of this task:


function randomValueFromArray(array) {
    const random = Math.floor(Math.random() * array.length);
    return array[random];
}

var storyText = 'It was 94 fahrenheit outside, so :insertx: went for a walk. When they got to :inserty:, they stared in horror for a few moments, then :insertz:. Bob saw the whole thing, but was not surprised — :insertx: weighs 300 pounds, and it was a hot day.';
var insertX = ['Willy the Goblin', 'Big Daddy', 'Father Christmas'];
var insertY = ['the soup kitchen', 'Disneyland', 'the White House'];
var insertZ = ['spontaneously combusted', 'melted into a puddle on the sidewalk', 'turned into a slug and crawled away'];

randomize.addEventListener('click', result);

function result() {
    var newStory = storyText;
    var xItem = randomValueFromArray(insertX);
    var yItem = randomValueFromArray(insertY);
    var zItem = randomValueFromArray(insertZ);

    newStory = newStory.replace(':insertx:', xItem);
    newStory = newStory.replace(':inserty:', yItem);
    newStory = newStory.replace(':insertz:', zItem);

    if (customName.value !== '') {
        const name = customName.value;
        newStory = newStory.replace('Bob', name);
    }

    if (document.getElementById("uk").checked) {
        const weight = Math.round(300 / 14) + ' stone';
        const temperature = Math.round((94 - 32) / 1.8) + ' centigrade';
        newStory = newStory.replace('300 pounds', weight);
        newStory = newStory.replace('94 fahrenheit', temperature);
    }

    story.textContent = newStory;
    story.style.visibility = 'visible';
}
***
## Academic Qualifications:
* __Belarusian State Academy of Communications__, Bachelor's degree in operation of telecommunications networks
* __Codebrainers Sp. z o. o.__, Full Stack Bootcamp course