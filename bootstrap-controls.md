1. bootstrapNumber控件，让加减号只在input元素获得焦点时才显示：

```
  $('input.foo').focus(function(){ $(this).siblings('span.input-group-btn').show(); });
  $('input.foo').blur(function(){ $(this).siblings('span.input-group-btn').hide(); });
```
