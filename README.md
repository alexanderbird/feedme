# Feed Me!

A static site that shows a count-up timer to use instead of a clock for new parents.
Because who cares if it's 11 pm or 5 am, it only really matters how long until the
next feeding.

The idea is to open it on a phone that's plugged in and place it in front of your alarm
clock.

Demo at [feedme.abird.ca](http://feedme.abird.ca)

## Deployment

It's a static html site -- do with it what you will. feedme.abird.ca uses an AWS S3 bucket and Route 53.

## Usage

- When you load the page, it starts counting up.
- At 3:00, it gongs.
- When you click/touch the screen, the gonging stops.
- Reload the page to restart the timer.

# Attributions

- Font: https://www.dafont.com/alarm-clock.font
- Sound: http://soundbible.com/1531-Temple-Bell.html
- Timing library: http://countdownjs.org/
