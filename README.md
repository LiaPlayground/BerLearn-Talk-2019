<!--
author:   Yo
email:    your@email.com
version:  0.1.0
language: en
narrator: US English Female

import: https://raw.githubusercontent.com/liaTemplates/vtk/master/README.md

-->


# LiaScript - An open-courSe development system


LiaScript, in contrast to all authoring systems, is not a tool, it is a language
based on Markdown, designed to be easy to learn and to enable everyone to create
and share high-quality educational content or at least participate in this
process.

## Education is a Business

I am sorry to disappoint you, but we all screwed up. Although the internet was
created to share information freely, education is becoming more and more a
business its not only the increase of textbook prices, it is the growing number
of private universities or schools, expensive MOOCs.

## The Main Problem ..

The main problem is, that most of us are simply cut of from the process of
creating content. Of course, you can use YouTube, if you like your voice and
have basic video-cutting skills, but a video is not interactive or easy to
change. You can program your interactive courses, but this is even more
challenging and time consuming. Or there is this thing called
Learning-Management-System, that in most cases also have a high learning curve
and require you to be always online. So in most cases, people get stuck to
simple text formats and share pdfs, word-documents, or powerpoints.

Imagine we could use simple text-documents and create YouTube-like screencast
presentations, interactive and freely programmable experience, with common
features from LMS.


## BerLearn 2019

On the next slide, I recorded a simple LiaScript development process. On the
left you will see the text-format and on the right, the generated output, that
is updated every time, when is hit save.

### Demo

    --{{0}}--
Simply use hash-tags to divide your document into sections, subsection,
sub-subsections, and so on. This is our schedule for today, you will learn how
to create content, define animations, quizzes, include multimedia content, live
coding and other fancy stuff.

     {{0-1}}
!?[vido](vid/BerLearn1.mp4?1)<!-- autoplay="autoplay" style="width:100%" -->


    --{{1}}--
You can simply start typing, paragraphs are text-blocks separated by newlines.
List ordered and ordered, you can have tables, and more. What LiaScript adds
is for example the possibility to use ASCII-art not only to draw diagrams.

     {{1-2}}
!?[vido](vid/BerLearn2.mp4?2)<!-- autoplay="autoplay" style="width:100%" -->

    --{{2}}--
Most PowerPoint-presentations are like, showing a bullet-point while someone
explains something about it. Well in LiaScript you only have to add double
braces with a number to indicate when something should appear or disappear. Add
two minuses around it, an the content gets spoken out loud.

     {{2-3}}
!?[vido](vid/BerLearn3.mp4?3)<!-- autoplay="autoplay" style="width:100%" -->


    --{{3}}--
How would you define a quiz only with a typewriter? Quizzes in LiaScript are
always associated with brackets. You can implement a muliplechoice quiz with
this checkbox-like notation, where the X marks the element to be checked.
A singlechoice quiz is simply a radio-button like representation with
parenthesses. You can add as many lines, even hints, or more detailed
explanations. And there are much more quizzes available.

     {{3-4}}
!?[vido](vid/BerLearn4.mp4?4)<!-- autoplay="autoplay" style="width:100%" -->


    --{{4}}--
These are 4 different links. In Markdown you add brackets in front of it and put
the link into paretheses, to get a named link. If you add a exclamation-mark in
front of it, you indicate that it is an image. That is Markdown. In LiaScript
you can add a questionmark to indicate that it is sound, in this case a
soundcloud link. And if you combine an image with sound you define a video.

     {{4-5}}
!?[vido](vid/BerLearn5.mp4)<!-- autoplay="autoplay" style="width:100%" -->


    --{{5}}--
Three back-ticks are the Markdown syntax to indicate source-code. In LiaScript
you can add a title to it, and a script-tag and you get executable code, that is
editable, with its own linear versioning system.

     {{5-6}}
!?[vido](vid/BerLearn6.mp4)<!-- autoplay="autoplay" style="width:100%" -->

     {{6-7}}
!?[vido](vid/BerLearn7.mp4)<!-- autoplay="autoplay" style="width:100%" -->


## Whats Next?


1. PWA

2. More distribution


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
| :--------- | ---------: |
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

@VTK.load(https://data.kitware.com/api/v1/file/58e665158d777f16d095fc2e/download)
