# Envision-XR-Demo

Formsubmit.co was used. You must consider changing these lines before deployment.
```
<form id="wf-form-Contact-1-Form" name="wf-form-Contact-1-Form" data-name="Contact 1 Form" method="post" class="combine-form_form-2" data-wf-page-id="64b10231df92ef567719d5e9" data-wf-element-id="f72938f2-1d94-03aa-0852-e654dd82dab3" action="https://formsubmit.co/zhangtianhang0405@outlook.com">
```
Change the email address after {action=} to a business email. Follow the format https://formsubmit.co/email here

```
<input type="hidden" name="_next" value="https://donniezhangcn.github.io/Envision-XR-Demo/finish-tc.html">
```
Change the url so the web browser could redirect to finish page. MUST BE A URL, NOT A PATH

```
<input type="hidden" name="_captcha" value="false">
```
If you want to turn Captcha on, set value="true". This may block some mainland users.
