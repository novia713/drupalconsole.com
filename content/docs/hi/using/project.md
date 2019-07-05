# परियोजना का उपयोग

ड्रुपल कंसोल कमांडो के दो प्रकार प्रदान करता है, `stand alone` और `container aware` कमांडो|

**Stand alone commands:**
ये आदेश एक Drupal 8 साइट रूट के बाहर चला सकते हैं|

**Container aware commands:**
ये आदेश एक Drupal 8 साइट रूट के भीतर चलाया जाना चाहिए|

### एक Drupal साइट रूट के बाहर Drupal कंसोल को चलाना
आप Drupal कंसोल अपने सिस्टम पर किसी भी निर्देशिका फार्म चला सकते हैं Drupal के जड़ को परिभाषित करने के लिए विकल्प आदेश निष्पादन `--root` में उपयोग होने के द्वारा|
```
$ drupal --root=/var/www/drupal8.dev cr all
```

**NOTE:** संभव संदेशों जब एक Drupal साइट रूट के बाहर ड्रुपल कंसोल को चलाएं पर और कोई `--root` विकल्प प्रदान नहीं|

एक Drupal 8 साइट रूट के बाहर परियोजना चल रहा है, निम्न संदेश दिखाया जाएगा|
> उपलब्ध सभी कमांडों को सूची के क्रम में दिखने के लिए, आप एक Drupal रूट निर्देशिका के अंदर इस चलाना चाहिए|

एक Drupal 8 साइट रूट के बाहर परियोजना चल रहा है, लेकिन साइट अभी तक स्थापित नहीं है, निम्न संदेश दिखाया जाएगा|
> पहले आपको Drupal स्थापित करना चाहिए उपलब्ध सभी कमांडों को सूची के क्रम में दिखने के लिए|