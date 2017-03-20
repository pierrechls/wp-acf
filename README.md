# Advanced Custom Fields

> Custom fields. Made easy. Use the Advanced Custom Fields plugin to take full control of your edit screens & custom field data. [https://wordpress.org/plugins/advanced-custom-fields/](https://wordpress.org/plugins/advanced-custom-fields/)

## 🔮 How to use it

#### Download and activate

- **Clone** the project `git clone git@github.com:pierrechls/wp-acf.git`
- **Upload** the *advanced-custom-fields* folder to the */wp-content/plugins/* directory
- **Activate** the plugin through the *Plugins* menu in WordPress

#### Create all your custom fields

Please follow the [user guides](https://www.advancedcustomfields.com/resources/creating-a-field-group/).

#### Add your custom fields on your template

```php
<?php $field = get_field($field_name, $post_id, $format_value); ?>
```

## 📚 Documentation

If you're a PHP developer, please refer to the [documentation](https://www.advancedcustomfields.com/resources/).

### 