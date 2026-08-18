# Create Data Sources

In order to build consistent data 'columns' in your records, you will need Data Sources mapped correctly, as these will be the basis of your segments and your automation.
Review the Element training for details on using Data Sources: https://help.element451.com/en/articles/2066888-data-sources

## Step 1: Do I need a Data Source?

That's a good question.  If you plan to reference a list of choices or options regularly across multiple forms and have data imports map into the same data column, you should use a Data Source.
Using a Data Source for a field will ensure data integrity when trying to make segments or doing reporting. It should show errors when your data is not being mapped correctly due to a typo or other input error, allowing you to catch the problem early.

For Example:

* Choosing a Degree Option/Concentration
* Choosing an Enrollment Term
  

If you are not planning to use the data regularly, or it's a text entry box, you do not need a Data Source, and can just make a Custom Form Field.

>[!WARNING]
>Since all of COE uses a single instance, using any system data sources in forms will cause additional or subsequent submissions to overwrite.

For example:

Suppose you want to make an interest form and want to know if someone is interested in a Master's or PhD.

You might think about using the Intended Degree field:

![Intended Degree](/Assets/degreedatasource.png)

This field maps to the 'Degrees' Data Source

![Degree Data Source](/Assets/degreedatasource.png)

This lets your have a dropdown list of majors to select from.

However! 

If another department decides to use the same Intended Degree field in their form, and the user submits another form for their department, it will overwrite the original submission.  

So if a person is interested in a PhD in your department, submits the form, and then a Master's degree for another department, and submits the form later, it will overwrite the PhD interest with Master's Degree interest.

>[!TIP]
>For this reason, you should only use system fields for information that will not change, like name, address, phone number, email, etc.
>If you need information unique to your department, you should create a custom form field, and maybe a Data Source (See Step 1 Above)

