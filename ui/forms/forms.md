# Forms

##Preface

This document offers a set of ** guidelines ** concerning design and construction or online forms.
Most of the topics mentioned below follow the general **best practices** that apply to form design. It is strongly recommended to follow these guidelines in order to achieve a consistent user experience throughout the many different applications that exist within the Antwerp brand architecture.

Deviations are possible, but always ensure that they are properly considered.

Also view the [sample form](https://xd.adobe.com/view/f23474ba-6a8e-4a20-463d-03c5343d956b-8405/?fullscreen) where most of the principles below are visually clarified.

## General

### Less is more

**Avoid surplus questions**. Each field in a form can become an obstacle to complete the form. Questions asked for obvious reasons will be perceived less as a threshold.

### Avoid distraction

When a form contains the main task of a page, make sure that the user can focus on that task as good as possible.

- Use **as few links as possible** that can distract the user or lead him away from the page.
- If navigation elements are necessary on the page, make sure that they **don't interfere** with the form and do not get in the way of the flow.

### Use of color

The use of color can help to better **understand** a form. However, try to limit the number of colors to 2 (primary and possibly secondary color). Additionally, validation elements may retain their own specific color (green, yellow, red).

_Note: Colors alone are not enough. People with some form of **color blindness** must be able to interpret the same message._

### Use of images and icons

Images and icons can help the user to "read" a form quickly. However, make sure that it does not become an excess. Use visual elements that are **generally known**, stick to the style guide and adhere to the "Less is more" principle.

### Auto focus

The use of autofocus **must be properly considered**.
Often it can help the user to **quickly** start a certain action or a task. A good example here is the Google homepage, where in most cases one will immediately start with a search action.

However, in many cases this can also be perceived as **unexpected or unwanted**:

- Sometimes users do not see that a field has focus, which can lead to annoying or confusing situations.
- People using screenreaders often have no idea where they are on the page when a certain field automatically attracts focus.

## Structure

`>> ACCOMPANYING INFO (NON-A-STAD FORMS)`

A form that is well structured will help the user to **understand** what is being asked of him and **how much effort** it will require to complete.

### Align

Limit the number of fields per line to 1 and **align left**. This ensures that the user only has to scan in 1 direction (vertically) and not always have to make horizontal movements in between.

###Sort

Use a **logical order**. Some sets of data are always shown in the same logical order.

For example, a typical order for **address data** is.

`1. street → 2. house number → 3. zip code → 4. location.`

When requesting the **name**, a common mistake that often leads to confusion is this:

`1. name → 2. first name`

"Name" can be both first name and last name. It is only when the user sees the following field ('first name') that he knows what is expected within the 'name' field.
The logical order (and name) here is:

`1. first name → 2. last name`

### Grouping

By grouping specific form fields you help the user in building a **mental model** of the form. This way he can somehow estimate what is expected of him. The use titles (field sets) further reinforces this.

A good practice for creating groups is around 6 fields. If there are more than 6 fields in a group, it may sometimes be advisable to investigate whether further grouping is possible.

### Multiple steps

Splitting a form into multiple steps can help it to be perceived as less intimidating.

But here applies the same rule: ensure a logical sequence of steps and clearly state in **which step** the user is at any time.

## Input fields

###Width

As a rule of thumb it can be stated that the width of input fields on desktop can take up 4/12 or 6/12 of the page grid.
On mobile they can span the entire width of the grid. The reason for this is so they can be easily selected by both left and right-handed people.

###Type

#### Free input

The use of the **correct type** of input fields can considerably facilitate the input for the user. Certainly on mobile, a specific input type ensures that the most appropriate keyboard is also displayed.

- Input type = "**text**" shows the standard keyboard
- Input type = "**email**" shows the standard keyboard with additional '@' and '.com'
- Input type = "**tel**" shows a numeric keypad (0-9)
- Input type = "**number**" shows a keyboard with numbers and punctuation marks
- Input type = "**password**" ensures that the entered characters are not displayed
- Input type = "**date**" shows the native (mobile) date selector
- Input type = "**datetime**" shows the native (mobile) date and time selector
- Input type = "**month**" shows the native (mobile) month / year selector

*NOTE: some input types can have unwanted behaviour or appearance on desktop browsers*

#### Predefined lists

Both radio buttons and checkboxes are preferably left-aligned and placed underneath each other.

In terms of user-friendliness, radio buttons are preferable above select boxes. They are easier to scan and less interaction is needed to make a choice:

- **Radio button**: 1 click is enough

- **Select box**: open click, possibly scroll, select.

Only if the list becomes unusable for a long time (eg countries, city names, street names ...), the use of a select box or autocomplete list may be appropriate.

## Required or not?

Most usability studies state that indicating a field as optional is preferred above indicating it as required. 

However, the use of an asterisk to mark required fields has been the way to go on most of the Antwerp websites. 

Also the asterisk is recognised by most of the internet users as an indication for required fields.

Therefore we will advise to use the asterisk pattern (until further notice).

## Formatting

Some data can be written in various ways:

- National register numbers: with or without spaces, punctuation marks ...
- Bank account numbers: with or without spaces
- Telephone numbers: with prefixes +32, 0032, zone number with or without preceding zero or brackets
- Date and time notation: 21/7/19, 21/07/2019, 21-07-'19, 1h15, 01:12 ...
- ...

Ensure that it is clear to the user in which format he has to enter data. Tools such as a simple **example** in the help text, an **input mask** or **intelligent form processing** can be useful here.

*NOTE: Take into account that users may enter unexpected input values! (eg people with a different official birth date - 00-01-2004, different house numbers ...)`

## Labels

Labels must be placed above the input fields, aligned left.

They must contain **clear copy** that **can not cause confusion with other fields**.

## Help text

Help text is text under an input field that **clarifies the function and / or its use**.

It is not mandatory, but can reduce confusion in the case of more complex questions / answers (dates, identification codes, ...).

## Placeholders

Are usually **not recommended**.

Since placeholders disappear when completing a field, they can never fully fulfill both the function of label and that of help text.

In very exceptional cases, when the function of a field is obvious (eg a search field, in which the icon of a magnifying glass is also incorporated), a placeholder can receive a function as (extra) call-to-action.

Placeholders can also fulfill a function in filter fields, i.e. to show what effect an empty field has on the filtering.
> e.g. A field that filters on a certain ticket number can show as placeholder text: 'All tickets'.
>
> It is of course important that the accompanying label clearly describes the function of the filter field.

## Validation

If technically possible, apply **real-time** and **intelligent** validation as much as possible.
This ensures that the user remains focused and doesn't have to sort out and correct any errors afterwards.

# Action buttons (send, next, previous ...)

##Position

### Single page form

The send button is placed **at the bottom**, **aligned left** (together with all other form elements).

### Multi page form

A multi page form shows **2 buttons**, next to eachother at the bottom of each page (except for the first and the last page).

One button to send and the other to return to the previous step.

Alignment follows the same logic as with a single page form.

## Labels

The label on the send button must indicate **what the next step is**.

## Disabled

`>> UNDER CONSTRUCTION`

## Do not use a reset function

Reset buttons as they are offered in HTML reset the fields in the form back to their initial values. In most cases this means that they are emptied.

**Try to avoid reset buttons**: they are rarely used intentionally and when they are clicked by accident, it causes a lot of frustration for the user.

If a reset button does seem necessary, consider carefully how it should work without obstructing the user.

#Validation and feedback

Give **clear instructions** for each input field. Use the help text below an input field to provide examples, rules or instructions.

If the user tries to send an incorrect or uncompleted form, show him a general message near the send button or in overlay at the top of the screen. It must point out that things are not right. Also show a specific message below the field to which the error relates.

Errors shown with form fields preferably appear real-time, if possible, when filling in the field. In this way, the user remains focused on the action that is required of him.

If the form field is incorrect, indicate where the error is and describe what is wrong.

In the case of incorrectly entered data, give suggestions on how to correct (where possible).

Make sure that the visitor can prevent errors in forms by which critical and irreversible actions are carried out.

Automatic scrolling to a specific field is not recommended as it is not alway expected by the user. It can be confusing, especially in the case of long forms or devices with lower performance, where the scrolling goes either to fast or not smooth.

# Accessibility (WCAG)

## Visual

### Use of color

Colors can help you to quickly interpret a form. Make sure that the message that these colors have to convey can also be interpreted unambiguously with other means (text, symbols, underlying code ...). *(1.4.1)*

### Icons

Icons that serve as visual support should not be recognized by screen readers if the purpose of the UI elements is sufficiently clear from the label or name. *(1.1.1)*

## Technical requirements

###Layout

Provide a **logical layout** that can be interpreted the same by different technologies.

The underlying structure (HTML) of a document must clearly state the purpose of the form.

### Labeling

Make clear what the purpose is of the different UI elements. Bear in mind that the difference between 2 fields is not always clear to users of supporting technologies (eg. screen readers).

Use clear descriptive headlines and labels.

If possible, ensure that the label of a field is reflected in the name of the field *(1.3.1 - 1.3.2 - 1.3.5 - 2.4.6 - 2.5.3)*

### Orientation and devices

The displaying on smaller or larger devices or the change of orientation of the device used should not affect how the form can be interpreted. *(1.3.4)*

###Keyboard

It must be possible for a user to complete and send a form **by using only the keyboard**.

Make sure that the **active element** is clearly distinguishable. *(2.1.1 - 2.1.2 - 2.4.3 - 2.4.7)*

### Automatic promotions

Do not allow a form field to initiate complex action when it receives focus or when it is filled in, unless this is expected by the user *(3.2.1 - 3.2.2)*.
