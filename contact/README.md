# Contact Form Section for Shopify

## Description

This section enables merchants to integrate a fully customizable contact form into their Shopify store. The form supports various fields including name, email, company, subject, phone, and up to five additional custom fields. All these fields can be toggled on and off through the Theme Editor. Moreover, the form is designed to be responsive and includes animations, ensuring a smooth user experience across all devices.

## Steps for Integration

1. **Save the Code**: Save this code as `contact-form.liquid` in the `sections` directory of your Shopify theme.
2. **Insert into Template**: Insert the section easily into the template where you want the contact form to display.(Just go add the new section like any other block)
3. **Configure via Theme Editor**: Use the Theme Editor to configure form settings such as enabling or disabling specific fields, defining custom fields, and customizing visual elements like color scheme, padding, and button rounding.
4. **Edit Localization File**: Navigate to your theme's localization file, commonly named `en.default.json`. Edit the keys under `"contact" -> "form"` to customize text labels, success and error messages.

## Customization

### General Settings

- **Heading**: The title of the contact form section. Default is "Contact form".
- **Heading Size**: Choose between h0, h1, and h2 sizes for the form's heading.
- **Color Scheme**: Pick a predefined color scheme for the form. Default is "background-1".

### Layout and Spacing

- **Padding Top**: Adjust the padding at the top of the section, ranging from 0 to 100 px. Default is 36 px.
- **Padding Bottom**: Adjust the padding at the bottom of the section, ranging from 0 to 100 px. Default is 36 px.

### Form Fields

- **Show Name Field**: A checkbox to toggle the visibility of the Name field. Default is enabled.
- **Show Email Field**: A checkbox to toggle the visibility of the Email field. Default is enabled.
- **Show Company Field**: A checkbox to toggle the visibility of the Company field. Default is enabled.
- **Show Subject Field**: A checkbox to toggle the visibility of the Subject field. Default is enabled.
- **Show Phone Field**: A checkbox to toggle the visibility of the Phone field. Default is enabled.
- **Show Comment Field**: A checkbox to toggle the visibility of the Comment field. Default is enabled.
  
### Custom Fields

- **Number of Custom Fields**: Choose the number of custom fields to include, ranging from 0 to 5.
- **Custom Field Labels**: Customize the label text for each custom field. Defaults are "Custom Field 1" to "Custom Field 5".

### Button Settings

- **Button Corner Rounding**: Choose the roundness of the submit button corners. Options are "None", "Small", "Medium", and "Large". Default is "None".


## Localization

For custom text labels, success and error messages, you can edit the appropriate keys in your theme's localization file. The relevant JSON section is under `"contact" -> "form"`.

### Sample JSON for Localization

```json
"contact": {
  "form": {
    "title": "Contact form",
    "name": "Name",
    "email": "Email",
    "phone": "Phone number",
    "comment": "Comment",
    "send": "Send",
    "post_success": "Thanks for contacting us. We'll get back to you as soon as possible.",
    "error_heading": "Please adjust the following:",
    "Company": "Company",
    "Subject": "Subject",
    "custom_field_label_1": "Custom Field 1",
    "custom_field_label_2": "Custom Field 2",
    "custom_field_label_3": "Custom Field 3",
    "custom_field_label_4": "Custom Field 4",
    "custom_field_label_5": "Custom Field 5"
  }
}
```

> [!IMPORTANT]
> Make sure to update the localization file for every language your store supports to maintain consistency across different language versions.
