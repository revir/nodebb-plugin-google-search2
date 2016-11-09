# Description

This plugin redirect search queries to Google, which used by [V2MM](https://v2mm.tech/), you can see what happened when you search on [V2MM](https://v2mm.tech/).

# Credit

This plugin was modified from [BenLubar's nodebb-plugin-google-search](https://github.com/BenLubar/nodebb-plugin-google-search), only fixed one problem: BenLubar's original plugin blocked the hook "filter:search.query" with a dummy function, which leads the suggested topics widget not work, because that widget would call this api when it's on the topic's template.

