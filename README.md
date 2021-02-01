# **Online Journal**

![Mock up](wireframes/mockup.file)

Online Journal is a place where users can keep a private journal using their
most easily accessible internet-capable devices.

--- 

<a></a>

## Table of contents 
* [UX](#ux)
    * [User Goals](#user-goals)
    * [User Stories](#user-stories)
    * [Site Owners Goals](#site-owners-goals)
    * [User Requirements and Expectations](#user-requirements-and-expectations)
        * [Requirements](#requirements)
        * [Expectations](#expectations)
    * [Design Choices](#design-choices)
        * [Fonts](#fonts)
        * [Colors](#colors)
        * [Structure](#structure)
* [Wireframes and Flowcharts](#wireframes-and-flowcharts)
    * [Wireframes](#wireframes)
    * [Flowcharts](#flowcharts)
    * [Database Structure](#database-structure)
* [Features](#features)
    * [Existing Features](#existing-features)
    * [Features to be implemented](#features-to-be-implemented)
* [Technologies used](#technologies-used)
    * [Languages](#languages)
    * [Libraries and Frameworks](#libraries-and-frameworks)
    * [Tools](#tools)
* [Testing](#testing)
* [Deployment](#deployment)
    * [Local Deployment](#local-deployment)
    * [Heroku Deployment](#heroku-deployment)
* [Credits](#credits)

---

<a name="ux"></a>

## **UX**

<a></a>

### **Project Goals**

The goal of this project is to provide users with a space where they can cultivate their own
journal on the internet, using whichever internet-capable device is most easily accessible to them.
The finished site will be clean, efficient, and not so frilly that it becomes cluttered up or
difficult to navigate. The purpose of this site is to be personal, as opposed to a blog which
is intended to be shared.

### **User Goals**

* Ability to create my personal account.
* Ability to login to my personal account.
* Ability to logout of my personal account.
* Ability to create personal entries.
* Ability to edit personal entries.
* Ability to delete personal entries.
* Ability to use a search function for key words across entries.
* Responsiveness to different devices.

[Back to Top](#table-of-contents)

<a></a>

### **User Stories**

* As a user, I expect to be able to efficiently create my personal account.
* As a user, I expect to be able to efficiently login to my personal account.
* As a user, I expect to be able to efficiently logout of my personal account.
* As a user, I expect to be able to efficiently create personal entries.
* As a user, I expect to be able to efficiently edit personal entries.
* As a user, I expect to be able to efficiently delete personal entries.
* As a user, I expect to be able to efficiently search for key words across entries.

<a></a>

### **Site owners Goals**

* Provide users with a functional space to create a personal account.
* Provide users with a functional space to login to a personal account.
* Provide users with a functional space to logout of a personal account.
* Provide users with a functional space to create personal entries.
* Provide users with a functional space to edit personal entries.
* Provide users with a functional space to delete personal entries.
* Provide users with a functional search feature.
* Provide users with a site that is fully responsive and easy to use on various devices.
* Provide users with a secure site.

[Back to Top](#table-of-contents)

<a></a>

### **User Requirements and Expectations**

<a></a>

#### Requirements

* Navigate the site using the navbar.
* Be able to create my personal account.
* Be able to login to my personal account.
* Be able to logout of my personal account.
* Be able to create personal entries.
* Be able to edit personal entries.
* Be able to delete personal entries.
* Be able to efficiently search for key words across entries.
* Be able to do all of the above from various devices.
* Website is displayed appealingly and is secure.

<a></a>

#### Expectations

* Can tap/click on navbar links to direct around the site.
* Can trust that the site is secure and password locked.
* Can create my personal account.
* Can login to my personal account.
* Can logout of my personal account.
* Can create personal entries effectively.
* Can edit personal entries effectively.
* Can delete personal entries effectively.
* Can search my journal using key words.
* Can access and use my journal from various devices.
* Website is appealing, easy to use, and responsive.

[Back to Top](#table-of-contents)

<a></a>

### **Design Choices**

I searched the term "forest" in [Coolors](https://coolors.co/ "Coolors.co") to find the 
color scheme that I ultimately used for this site. I decided on this search term because
I wanted calming, relaxed colors that had a woodsy, natural vibe to them, an aesthetic
often associated with journaling. I chose to avoid using white as a background because
of the textual nature of this site - something I learned in my teaching courses is that
people with reading difficulties such as dyslexia often find reading on a white background
much more difficult than reading on a cream colored background. I also chose to avoid
white because of the digital nature of this site, and the connection between blue light 
given off by white screens and deterioration of sleep cycles.

<a></a>

#### Colors

![Color Palette](wireframes/color-palette.png)
 
*![#3F4238](https://placehold.it/15/3F4238/000000?text=+) `#3F4238`: Black Olive: I chose this as a header color because it has stark contrast and is easy to read. It
isn't quite black but it is close. 
*![#6B705C](https://placehold.it/15/6B705C/000000?text=+) `#6B705C`: Ebony: I chose this as a secondary text color because it is just different enough from Black Olive
to be easy to differentiate for users, but is still easy to read.
*![#FFE8D6](https://placehold.it/15/FFE8D6/000000?text=+) `#FFE8D6`: Champagne Pink: I chose this to be the background color of the main journal entry text fields because,
as noted earlier, white backgrounds for text can be more difficult for people with dyslexia and for general health.
Because this will be likely utilized in the evenings, and for lengths of time, this was taken strongly into account.
*![#CB997E](https://placehold.it/15/CB997E/000000?text=+) `#CB997E`: Antique Brass: I chose this to be the main background color for the site because it is a calming color that
accents the other colors used nicely.
*![#B98B73](https://placehold.it/15/B98B73/000000?text=+) `#B98B73`: Antique Brass: I chose this as a third level text color for links, buttons and highlighted text because it works
well with the other colors and isn't too dark to be a button color, but isn't too light to be a text color.

<a></a>

#### Fonts

The two fonts I used for this site are [Mukta](https://fonts.google.com/specimen/Mukta) 
and [Montserrat](https://fonts.google.com/specimen/Montserrat). I chose Mukta because it is sans-serif,
which is often easier to read, and chose Montserrat because it was one of the top paired fonts on Google Fonts.

<a></a>