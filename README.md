<!--
author:   André Dietrich
email:    LiaScript@web.com
version:  0.1.1
language: en
narrator: US English Female

logo:     https://secure.meetupstatic.com/photos/event/d/a/b/a/600_478375994.jpeg

comment:  BerLearn-Pitch-Talk about the need for a new domain-specific-language
          for creating free and open courses, and about the ease of using
          LiaScript to create them ;-)

link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css

import:   https://raw.githubusercontent.com/liaTemplates/vtk/master/README.md

-->


# LiaScript - An Open-courSe development system

    {{0-1}}
> **1.** Use the arrow buttons above for navigation
>
> **2.** Turn on your sound for the text output.

__By Dr. André Dietrich:__

* Website: http://LiaScript.github.io
* GitHub: https://github.com/andre-dietrich/BerLearn-Talk-2019
* LiaScript: https://liascript.github.io/course/?https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/README.md#1

---

![qr-code](https://api.qrserver.com/v1/create-qr-code/?size=222x222&data=https://liascript.github.io/course/?https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/README.md)<!--
style="height: 300px; border:1px solid #021a40;" -->
![BerLearn](img/BerLearn.png) <!-- style="float:right; height: 300px; border:1px solid #021a40;" -->




    --{{1}}--
LiaScript, in contrast to all authoring systems, is not a tool, it is a language
based on Markdown, designed to be easy to learn and to enable everyone to create
and share high-quality educational content or at least participate in this
process.

## Education as a Business

    --{{0}}--
I am sorry to disappoint you, but we all screwed up. Although the internet was
created to share information freely, education is becoming more and more a
business its not only the increase of textbook prices, it is the growing number
of private universities or schools, expensive MOOCs.

      {{0}}
![Problem](img/percentage.png)<!-- style="width: 80%" -->

_^Source: https://www.aeseducation.com/blog/infographic-the-skyrocketing-cost-of-textbooks-for-schools-students ^_

## The Main Problem ...

    --{{0}}--
The main problem is, that most of us are simply cut of from the process of
creating content. Of course, you can use YouTube, if you like your voice and
have basic video-cutting skills, but a video is not interactive or easy to
change. You can program your interactive courses, but this is even more
challenging and time consuming. Or there is this thing called
Learning-Management-System, that in most cases also have a high learning curve
and require you to be always online. Thus, in most cases, people get stuck to
simple text formats and share PDFs, Word-documents, or PowerPoints.

![YouTube](img/YouTube.png)<!--
style="width:23%; animation-delay: 5s;"
class="animated fadeIn"
--> ![Html](img/HTML.png)<!--
style="width:23%; animation-delay: 13s;"
class="animated fadeIn"
--> ![Html](img/Moodle.png)<!--
style="width:23%; animation-delay: 19s;"
class="animated fadeIn"
--> ![Html](img/word.png)<!--
style="width:23%; animation-delay: 28s;"
class="animated fadeIn"
-->

    --{{1}}--
Imagine we could use simple text-documents and create YouTube-like screencast
presentations, interactive and freely programmable experience, with common
features from LMS.


## BerLearn 2019

    --{{0}}--
On the next slide, I recorded a simple LiaScript development process. On the
left you will see the text-format (course-content) and on the right, the
generated output, that is updated every time, when I hit save.

### Demo

    --{{0}}--
Simply use hash-tags to divide your document into sections, subsection,
sub-subsections, and so on. This is our schedule for today, you will learn how
to create content, define animations, quizzes, include multimedia content, live
coding and other fancy stuff.

     {{0-1}}
!?[![BerLearn1](http://i3.ytimg.com/vi/PGulF4H6iC0/maxresdefault.jpg)](https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/vid/BerLearn1.mp4)<!--
autoplay="autoplay" style="width:100%"
-->


    --{{1}}--
You can simply start typing, paragraphs are text-blocks separated by newlines.
List ordered and ordered, you can have tables, and more. What LiaScript adds
is for example the possibility to use ASCII-art not only to draw diagrams.

     {{1-2}}
!?[![BerLearn2](http://i3.ytimg.com/vi/S9lzG-4I0uc/maxresdefault.jpg)](https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/vid/BerLearn2.mp4)<!--
autoplay="autoplay" style="width:100%"
-->


    --{{2}}--
Most PowerPoint-presentations are like, showing a bullet-point while someone
explains something about it. Well in LiaScript you only have to add double
braces with a number to indicate when something should appear or disappear. Add
two minuses around it, an the content gets spoken out loud.

     {{2-3}}
!?[![BerLearn3](http://i3.ytimg.com/vi/4xC0v6d8osA/maxresdefault.jpg)](https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/vid/BerLearn3.mp4)<!--
autoplay="autoplay" style="width:100%"
-->


    --{{3}}--
How would you define a quiz only with a typewriter? Quizzes in LiaScript are
always associated with brackets. You can implement a multiple-choice quiz with
this checkbox-like notation, where the X marks the element to be checked. A
single-choice quiz is simply a radio-button like representation with
parenthesis. You can add as many lines, even hints, or more detailed
explanations. And there are much more quizzes available.

     {{3-4}}
!?[![BerLearn4](http://i3.ytimg.com/vi/Q1RxgvltEhA/maxresdefault.jpg)](https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/vid/BerLearn4.mp4?4)<!--
autoplay="autoplay" style="width:100%"
-->


    --{{4}}--
These are 4 different links. In Markdown you add brackets in front of it and put
the link into parenthesis, to get a named link. If you add a exclamation-mark in
front of it, you indicate that it is an image. That is Markdown. In LiaScript
you can add a question mark to indicate that it is sound, in this case a
[soundcloud](https://soundcloud.com) link. And if you combine an image with
sound you define a video.

     {{4-5}}
!?[![BerLearn5](http://i3.ytimg.com/vi/V-PtMm5IErs/maxresdefault.jpg)](https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/vid/BerLearn5.mp4)<!--
autoplay="autoplay" style="width:100%"
-->


    --{{5}}--
Three back-ticks are the Markdown syntax to indicate source-code. In LiaScript
you can add a title to it, and a script-tag and you get executable code, that is
editable, with its own linear versioning system.

     {{5-6}}
!?[![BerLearn6](http://i3.ytimg.com/vi/1tAdd8ORXsE/maxresdefault.jpg)](https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/vid/BerLearn6.mp4)<!--
autoplay="autoplay" style="width:100%"
-->


    --{{6}}--
You may have noticed the script-tag that defines how code is executed. LiaScript
has its own macro-system that allows to hide and reuse JavaScript, CSS, HTML.
Even more than that, courses can import this functionality from other courses.
Like in the example, only one command is required to load a medical data-set and
visualize it.

      {{6}}
!?[![BerLearn7](http://i3.ytimg.com/vi/kpJvm955nLg/maxresdefault.jpg)](https://raw.githubusercontent.com/andre-dietrich/BerLearn-Talk-2019/master/vid/BerLearn7.mp4)<!-- autoplay="autoplay" style="width:100%" -->

## Publish your Course

    --{{0}}--
You only have to upload your text-file somewhere, preferably on
[GitHub](https://github.com), and then pass the link to the
[LiaScript-website](https://LiaScript.github.io). The course will be immediately
loaded and you will get an unique URL, that you can share with others.  A
JavaScript-application is responsible for loading the course and interpreting
it. No login, no setup, everything happens within the browser and all states are
stored locally.

![share](img/share.png)<!-- style="width: 100%" -->

## Whats Next?

1. **PWA** : Progressive Web App

       --{{0}}--
   The next step is to implement a PWA, a website that can be installed on
   SmartPhones and tablets, which can be used offline as well as the courses,
   which only have to be loaded once.

2. More distribution & communication

       --{{1}}--
   What is currently missing, is the possibility for shared classrooms, chats,
   and more, where teachers see the results of quizzes and surveys and can
   interact freely with students in their group.


# Original Demo

## Structuring

      --{{1}}--
Paragraphs are simple
text-blocks separated
by a line-breaks.

        {{1}}
1. Lists can either
   have an **order**
2. or be simple ...
   * bullet-points
   + ...



      {{2}}
| Lists are  | Simple too |
|:-----------|-----------:|
| {4}{left}  | {5}{right} |


     {{3-4}}
                         Multiline
    1.9 |    DOTS
        |        *
      y |     *     *
      - |    *       *
      a |   *         *
      x |  *           *
      i | *             *
      s |r r r r r r r r * r r r r
        |                   * *  *
     -1 +-------------------------
        0         x-axis         1


## Quizzes

### MultipleChoice


[[ ]] Add as many elements as you want?
[[X]] The X marks the correct answer!
[[X]] ... this has to be selected too ...
[[ ]] ... this is wrong ...

### SingleChoice

    [( )] This is wrong.
    [(X)] The only correct option.
    [( )] Still not right.
    [[?]] give some hints
    [[?]] more hints
*********************

the solution might
be even more complicated

$$
   \sum_{i=1}^\infty\frac{1}{n^2}
        =\frac{\pi^2}{6}
$$

*********************

## Images & Multimedia

[link](https://de.wikipedia.org/wiki/Alexander_von_Humboldt)

![image](https://upload.wikimedia.org/wikipedia/commons/f/f3/AvHumboldt.jpg)

?[sound](https://soundcloud.com/bonifansius/bedtime-baby-lullaby-classical-music-mozart-bach-beethoven-pachelbel-sleep-music-1-hour)

!?[youtube](https://www.youtube.com/watch?v=8pTEmbeENF4)


## LiveCoding & More

``` js     +EvalScript.js
let who = data.first_name + " " + data.last_name;

if(data.online) {
  who + " is online"; }
else {
  who + " is NOT online"; }
```
``` json    +Data.json
{
  "first_name" :  "Sammy",
  "last_name"  :  "Shark",
  "online"     :  true
}
```
<script>
  // insert the JSON dataset into the local variable data
  let data = @input(1);

  // eval the script that uses this dataset
  eval(`@input(0)`);
</script>


## Macros

> Please be patient, loading the dataset may take a while.

@VTK.load(https://data.kitware.com/api/v1/file/58e665158d777f16d095fc2e/download)
