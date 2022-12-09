# Nikita Meshcheriakov


## Contacts for communication
[Telegram](https://t.me/Spayker669)


## Info
Unfortunately, I have no work experience, I'm just learning and striving for something new and interesting, I want to learn new things and improve my skills

## Skills
HTML, CSS

## Code
'''
const scroller = document.querySelector('.scroller');
const nextBtn = document.querySelector('.btn.next');
const prevBtn = document.querySelector('.btn.prev');
const itemWidth = document.querySelector('.item').clientWidth;

nextBtn.addEventListener('click', scrollToNextItem);
prevBtn.addEventListener('click', scrollToPrevItem);

function scrollToNextItem() {
if(scroller.scrollLeft < (scroller.scrollWidth - itemWidth))
  scroller.scrollBy({left: itemWidth, top: 0, behavior:'smooth'});
else
  scroller.scrollTo({left: 0, top: 0, behavior:'smooth'});
}

function scrollToPrevItem() {
if(scroller.scrollLeft != 0)
  scroller.scrollBy({left: -itemWidth, top: 0, behavior:'smooth'});
else
  scroller.scrollTo({left: scroller.scrollWidth, top: 0, behavior:'smooth'});
}
'''

## Work experience
Missing

## Education
Passed a course in HTML, CSS, and not a complete course in Javascript

## English language no more than A-2

