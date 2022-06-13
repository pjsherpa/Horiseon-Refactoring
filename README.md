# Horiseon-Refactoring
UCB Challenge 1:
Note:
Please note comments are present in both html and css codes.
Please note as per Standard rules for comments everything is in present tense. 

This has the following in it:
1. Definition of refactoring and accesibility.
2. Note to Marketing Agency.
3. Change for HTML & CSS coding(to make semantic HTML elements,logical structure independent of styling and positioning,accessible alt attributes for images, sequential order and change in title name)
4. Deployment(consists of URL for Github Repository & Live URL) 


Refactoring is a disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behaviors.

HTML CSS Git Challenge: Code Refactor
challenge involves a very important aspect of web development: <b>accessibility.<b>
Accessibility can be viewed as the "ability to access" and benefit from some system or entity. The concept focuses on enabling access for people with disabilities, or enabling access through the use of assistive technology.
However:
Color combinations to avoid for people with color blindness include: Blue and Gray. 

Note to Marketing Agency:
Picking Blue and Gray colors for this webpage can lead an issue for accessibility for color blind people. To take in mind as Refactoring relates to only restructuring of internal structure and not external behaviors. No change made on the colors for this.

Changes:
For HTML:
  
  <--head-->
1. Change title name from website to Horiseon also add <meta name="“viewport”" content="“width=device-width," initial-scale="1.0&quot;">.
    Meta viewport added to make it accessible for viewing the webpage in hand held devices.
    
    <--Body-->
2. Change div class="header" to <header> remove div from list section to make it semantic HTML element.
3. Change div to nav to make it semantic HTML element.
4. Add "main" to make it a semantic HTML element.
5. Change div to section to make it a semantic HTML element.
6. Change div to article to make it semantic HTML element.
7. Link search-engine-optimization to function correctly.
8. Changed class name to "box" for "search-engine-optimization", "online-reputation-management" and "social-media-marketing" to consolidate CSS coding on section class "content".
9. All three class names are now "benefit-lead" which was the first class, change made for benefit-brand & Management to consolidate CSS coding on section class"benefits".
9. Add alt attributes on all 6 images.
10. Change div to aside to make it semantic HTML element on section class "benefit".
11. Change div to footer to make it semantic HTML element.
12. Change Footer from h2 to h4 to meet sequential order.
  
For CSS:
1. Change class (.header) to element(header).
2. Change div to nav. 
3. Consolidate class and consolidate codes for changes made above.
4. Change heading to meet sequential order for html so change footer to h4 from h2 
  (basically updated changes made on html)


Deployment:
URL for GitHub Repository
https://github.com/pjsherpa/Horiseon-Refactoring

Live URL page:
https://pjsherpa.github.io/Horiseon-Refactoring/
  
Up and running with no issues with no errors.
      
 ![Screen Shot 2022-06-12 at 7 50 45 PM](https://user-images.githubusercontent.com/105903416/173270938-c7e66e19-1146-4bba-b0af-8708bcb38e8b.png)
