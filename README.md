[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/61wuBnVw)
# Instructions

https://docs.google.com/document/d/1pmo_NX_ZfmEtSR7PkO8wVo0BXL2NZ5HNvDyUfYcMSJY/edit?usp=sharing

# Responsiveness and web Accessibility
### Live links:
- https://mru-comp2511-f2024.github.io/a2-responsiveness-and-accessibility-SirDre/index.html
- https://agrigadget.netlify.app

# Part 2
### Questions:
- Document the category of issues that you identified through the manual and automated analysis above.
  <pre>
  - layout issues and improvements:
      Issues:
        - Issues spacing between elements
        - Issues alignment of elements
        - Better grid and flexbox implementation
      Improvements:      
        - Properly aligned elements
        - Better organized breakpoints
        - Enhanced responsive behavior
  - Styling:
      Issues:
        - Issues determine which is a better CSS property
        - Issues implementing better spacing and alignment
      Improvements:
        - Designing with modern and clean layout in mind
        - Implement clear visual hierarchy in HTML 
        - Combined similar rules
        - Removed redundant styles
  - Structure:
      Issues:
        - Remove dl/dd with semantic div structure
        - Revise item pages due to responsive and accessibility issues
      Improvements:
        - Implemented proper form groups
        - Improved radio button and checkbox grouping
        - Improved better button organization
  - Accessibility:
      Issues:
        - Struggle with labeling and additional requirement for forms accessibility
        - Previous form structure with semantic HTML was not functioning as I taught.
      Improvements:
        - Implement label and input associations using for and id attributes.
        - Included descriptive placeholders
        - Included title attributes for validation
        - Improved form structure with semantic HTML
  - Group Efforts:  
        Organization and planning.
        Restructing most of the pages.
        Trying to familized with the CSS rules.
    
  </pre>

- What kinds of changes did you have to make (I do not want a list here). Generalize the types of issues that you created when building your website, and then the general type of changes that you made to resolve those issues.
  <pre>
    A good user experience is logically an asset when designing website. Clear visual identification and error messaging are very important aspects of the experience. Often times bad and lazy design decisions, e.g., confusing colored elements, can cause the user to miss out on important alerts or instruction. The solution lies in giving error messages a bright color and clear language that stands out. Of course, full reliance on pop-up messages is a bad idea since some users have them all turned off.

    Issues such as ambiguity or vagueness in terminology when designing website can be a challenge. For example, vague descriptions can cause a considerable obstacle for users in the way that they need more time and energy to make sense of these terms. Such as, being asked to choose a “Salutation” instead of “Titles or Honorifics” the difference is not that slight and may lead to confusion. However, using clear, familiar, and task-oriented terminology that matches user expectation and experience could reduce confusion.

    Lastly, data input challenges arise when users find it hard to input data accurately since input fields are badly designed and controls do not match an anticipated data type. For instance, a field for a phone number that does not support another countries phone number format can lead to incorrect data inputs. However, improving form’s structure and its usability, thereby making it easy for the user to accurately input the required data.

  </pre>
- How do these accessibility changes connect with the Gestalt principles we discussed earlier this semester?


## Agriculture store

**Topic:  Agriculture store**

**Brand: AgriGadgets (agrigadgets.com or agrigadgets.ca )**

### Assignment Tasks & the person responsible

### Andre Gardiner:

**Responsiveness and Accessibility Mockup:**
- Consultation

**Responsiveness and web Accessibility Requirements:**
- A consistent look and feel for all pages
 - contact.html
 - how-to-buy.html
 - index.html
 - item-compact-pro-smoker-in-stainless-steel.html
 - item-extractor-essential-oils-12-liters.html
 - item-food-smoker-10030na-assembly-kit.html
 - item-polentera-p5tm.html
 - item-stainless-steel-container-nm007.html
 - shop.html
 - thank_you.html
 - who-we-are.html

**CSS Styling Requirements:**

- Use **external CSS files** - responsive.css
- All pages must use consistent font, margin, padding.
- Uses consistent design for the header and footer area in all pages. 
**Break points for small, medium, and large devices Requirements:**
<pre>
  /* wide desktop screen - additional */
  @media screen and (min-width: 1025px) {
  }
  /* desktop screen - additional */
  @media screen and (max-width: 1024px) {
  }
  /* ipad screen - required*/
  @media screen and (max-width: 790px) {
  }
  /* mobile screen - required */
  @media screen and (max-width: 590px) {
  }
</pre> 

### Nuel Amadi:

**Responsiveness and Accessibility Mockup:**
- **Sketch the layout and content structure**
 - contact.html
 - index.html

**Responsiveness and web Accessibility Requirements:**
- A consistent look and feel for all pages
 - contact.html
 - how-to-buy.html
 - index.html
 - item-compact-pro-smoker-in-stainless-steel.html
 - item-extractor-essential-oils-12-liters.html
 - item-food-smoker-10030na-assembly-kit.html
 - item-polentera-p5tm.html
 - item-stainless-steel-container-nm007.html
 - shop.html
 - thank_you.html
 - who-we-are.html

**CSS Styling Requirements:**

- Use **external CSS files** - responsive.css
- All pages must use consistent font, margin, padding.
- Uses consistent design for the header and footer area in all pages. 
**CSS Requirements:**
<pre>
  /* wide desktop screen - additional */
  @media screen and (min-width: 1025px) {
  }
  /* desktop screen - additional */
  @media screen and (max-width: 1024px) {
  }
  /* ipad screen - required*/
  @media screen and (max-width: 790px) {
  }
  /* mobile screen - required */
  @media screen and (max-width: 590px) {
  }
</pre>

### Sketches for the website and short description

- Ref: a1-html-and-css-mock-up.pdf (#TODO: put link)

### Bash Merge CMD:

<code>$ git remote add source-repo https://github.com/MRU-COMP2511-F2024/a1-responsiveness-and-web-accessibility-SirDre</code>

<code>$ git fetch source-repo</code>

<code>$ git merge source-repo/main</code>

<code>$ git pull source-repo main --allow-unrelated-histories</code>

<code>git add .</code>

<code>git commit -m "Merged from source repository"</code>

<code>git push origin main</code>

### Idea References:

**LOGO**

- https://www.canva.com/design/DAGUKZukXkY/m9hGYCouMnMMOT-Y5gQLLg/edit

**FONTS and ICONS**
- https://fonts.google.com

**Design:**

- https://www.amazon.com
- https://www.ebay.ca
- https://www.deere.com/en/agriculture/

**Items:**

- https://www.agritechstore.com
- https://www.deere.com/en/agriculture/

**Contents:**

- https://www.lipsum.com
- https://agriculture.canada.ca/en/sector/overview
- https://www.deere.com/en/agriculture/
- https://www.agritechstore.com
- https://www.nutrasource.ca/markets/agricultural-products/

