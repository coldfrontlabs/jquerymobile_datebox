Usage
=====

Using theme templates or form alter, you can add the proper attributes to initialize the datebox element

~~~~~~~~~~~~~~~~~~~~~~
Ex:

hook_form_ID_alter(&$form, &$form_state) {
  $form['datefield']['#attributes']['data-role'] = 'datebox';
  $form['datefield']['#attributes']['data-options'] = '{"mode": "calbox"} ';
}
~~~~~~~~~~~~~~~~~~~~~~

For a full list of options see http://dev.jtsage.com/jQM-DateBox/