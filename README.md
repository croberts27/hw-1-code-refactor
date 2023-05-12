# Horiseon Social Solution Services, Inc.

## Description
- - - -
This is the webpage for Horiseon Social Solution Services, Inc. They provide professional services in 'Social Media Marketing', 'Search Engine Optimization', 'Online Reputation Management', 'Lead Generation', 'Brand Awareness', and 'Cost Management'.

- - - -

## Acceptance Criteria

After hearing Horiseon's user story I worked with them to develop acceptance criteria for this refactoring project. The criteria for success is outlined below:

* **WHEN I view the source code**
* **THEN I find semantic HTML elements**
* **WHEN I view the structure of the HTML elements**
* **THEN I find that the elements follow a logical structure independent of styling and positioning**
* **WHEN I view the image elements**
* **THEN I find accessible alt attributes**
* **WHEN I view the heading attributes**
* **THEN they fall in sequential order**
* **WHEN I view the title element**
* **THEN I find a concise, descriptive title**
- - - -
## Code Refactoring

After reviewing the acceptance criteria it was determined that the sourcecode needed refactoring. An example of the original code is provided below:
```
<div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
```
It was determined that the structure of the `HTML` elements was not logical and needed semantic tags added. Here is an example of the end result:

```
<aside class="benefits">
        <article class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt = "icon depicting inbound lead generation flow" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </article>
        <article class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt = "brand awareness icon" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </article>
        <article class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt = "cost management icon" />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </article>
    </aside>
```
- - - -

## Screenshot

!["Horiseon Webpage"](/assets/images/horiseon-webpage.JPG "Horiseon Webpage Screenshot")

## Conclusion

After reviewing the acceptance criteria and refactoring the source code the webpage has been re-deployed. The new webpage can be found here: https://croberts27.github.io/hw-1-code-refactor/