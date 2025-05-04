
# Links marking guide

The aim of the tasks is to demonstrate an understanding of hyperlinks.

## Task 1

The first task covers some link basics — setting a link destination, giving it a descriptive title, and creating an email link.

The title needs to contain some supplemental information about the page that is useful but not essential for knowing what the linked page is about. If the subject was included on the email link, it really needs `%20` escape characters included so that you get spaces in the subject line. 

## Task 2

Our second task here tes<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8"/>
    <title>Whales!</title>
    <style>
      body {
        background-color: #fff;
        color: #333;
        font: 1em / 1.4 Helvetica Neue, Helvetica, Arial, sans-serif;
        padding: 1em;
        margin: 0;
      }

      h1 {
        font-size: 2rem;
        margin: 0;
        color: purple;
      }

      p {
        color: gray;
        margin: 0.5em 0;
      }

      * {
        box-sizing: border-box;
      }
    </style>
  </head>

  <body>

    <h1>Whales</h1>

    <p>You found our Whales page — well done!</p>

    <!-- Task 1: Link with title and email link -->
    <p>
      Learn more about whales on the 
      <a href="https://en.wikipedia.org/wiki/Whale" title="Comprehensive information about whales on Wikipedia">
        Wikipedia whale page
      </a>.
    </p>
    <p>
      Got questions? 
      <a href="mailto:oceanlife@example.com?subject=Whale%20Inquiry">Email our whale experts</a>.
    </p>

    <!-- Task 2: Absolute link, relative link, fragment link -->
    <p>
      Read fascinating facts on the 
      <a href="https://www.nationalgeographic.com/animals/mammals/facts/blue-whale">
        National Geographic Blue Whale page
      </a>.
    </p>
    <p>
      Visit our related page about 
      <a href="dolphins.html">Dolphins and their behavior</a>.
    </p>
    <p>
      Jump to the section on 
      <a href="#blue-whale">Blue Whales below</a>.
    </p>

    <!-- Task 3: Better link text + large download warning -->
    <p>
      For in-depth research, check out the 
      <a href="downloads/whale-study.pdf">Whale Research PDF</a> 
      <strong>(Warning: large download)</strong>.
    </p>

    <p>
      Watch the 
      <a href="videos/whale-documentary.mp4">Whale Documentary</a> 
      <strong>(Video, large file)</strong> to see them in action.
    </p>

    <!-- Fragment target -->
    <h2 id="blue-whale">Blue Whales</h2>
    <p>
      Blue whales are the largest animals ever known to have lived on Earth.
    </p>

  </body>
</html>
ts your knowledge of  absolute and relative paths, as well as link fragments. 

## Task 3

Our final task in this set is concerned with good practices for link text.

Basically, all three paragraphs need to be rewritten with good link text, and the third one needs to have a warning added to the link to say that it is a large download. 