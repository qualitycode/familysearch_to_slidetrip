
# Familysearch to slidetrip

[![Gitter](https://badges.gitter.im/qualitycode/familysearch_to_slidetrip.svg)](https://gitter.im/qualitycode/familysearch_to_slidetrip?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Or should I say slidetrip to familysearch?  Whatever.  This is the first of many projects to enhance slidetrip.com.

## What is slidetrip.com?

It is smart software that will create movies from your family history, with audio narratives, relevant pictures, a 3D earth, web page & book.

## To Do List:

Hook up the existing slidetrip.com slideshow generator to familysearch.org.  Currently slidetrip uses [GEDCOM](https://en.wikipedia.org/wiki/GEDCOM) files to generate online slideshows. These slideshows include audio, images, video, plus virtual trips to your ancestral lands via Google Earth or Google Maps.  Slidetrip converts the gedcom files into xml files.  People don't like creating GEDCOM files from their genealogy software.  So we need to use the api from familysearch.org as the source.  This makes it easier to use slidetrip.  Here are the steps that I see needing to be done to link slidetrip to familysearch:

 1. Create a one-page html file that will use the familysearch api to
    log in, choose a family name,
 2. Associate images in familysearch memories to events or names.
 3. Allow user to upload additional pictures to the familysearch
    memories. Format the family names and events into an xml object (see
    example xml:
    [obama.ged.xml](https://github.com/qualitycode/familysearch_to_slidetrip/blob/master/obama.ged.xml))

## Additional Sub Projects

After the above steps, following are additional sub projects that need to be done for the overall slidetrip project:

 1. After we get slidetrip running with familysearch, we need to
    re-write slidetrip.  It needs to be converted from Adobe Flash to
    javascript.
 2. Add collaboration.
 3. Tools to collaborate to create color picture books from photos and
    stories.
 4. There are other cool parts of this project, which will be documented
    later.

## To Get Involved

To get involved, join our discussion group and leave a message. See https://gitter.im/qualitycode/familysearch_to_slidetrip 

We need programmers, graphic designers, genealogy mentors. Programmers, we are using the MERN stack (Mongo, Express, React, Node.js, javascript, etc.)

We are using the FamilySearch APIs. Please visit https://familysearch.org/developers/ .

Here is the FamilySearch JavaScript SDK:  https://github.com/rootsdev/familysearch-javascript-sdk. 
