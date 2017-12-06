Helpful info:
1. To resolve positioning issues with full screen Reveal modal popups on iOS using Foundation - add <b>data-v-offset="0"</b> to the modal like this:

<pre>
```
    <div class="full reveal reveal-modal" id="site-reveal-menu" data-reveal data-overlay="false" data-v-offset="0">
      <div class="page-content">
        ...
      </div>
    </div>
    ```
</pre>

  Read about: https://github.com/zurb/foundation-sites/pull/9763#issuecomment-317281420
  
