* Block in CMS:
```PHP
{{block class='Magento\Framework\View\Element\Template' name='contactFormMap' template='Magento_Contact::html/contactMap.phtml'}}
```

* Block in PHTML:
```PHP
<?php $html = $this->getLayout()->createBlock('Magento\Cms\Block\Block')->setBlockId('marque_homepage')->toHtml(); ?>
<?php if ($html) : ?>
    <?php echo $html ?>
<?php endif; ?>
```

* Image:
```PHP
{{view url="images/demo.jpg"}}
{{media url="wysiwyg/clinic-setup/gait_analysis.jpg"}}
```

* Config:
```PHP
{{config path="web/unsecure/base_url"}}
```
