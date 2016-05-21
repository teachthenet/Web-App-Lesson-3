# Web-App-Lesson-3

Create a Google Form: https://docs.google.com/forms/

When done, click Send, then copy the code from the Embed tab. It should look like this:

```
<iframe src="https://docs.google.com/forms/d/1U3l9A9IQhV9S4htGRh5p_rgQzlyQPeK-02UF_yS_6ng/viewform?embedded=true" width="760" height="500" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
```

And add that to index.html in place of the existing iframe code.

Now back to your form. Click the Responses tab, click Create Spreadsheet. Open the spreadsheet, click File, Publish, and get the link. Stick the link in index.html in the variable named public_spreadsheet_url.

Now in index.html, you may need to update the variable names in the "row" variable, depending on what you named each field in the form.
