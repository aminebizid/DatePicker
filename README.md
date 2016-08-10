DatePicker

Usage:

ts

```typescript
this.date = new Date();
```

```html
<md-datetimepicker required="" placeholder="Start Date" [(ngmodel)]="date">
</md-datetimepicker>
```

With Form

```html
<md-datetimepicker required="" placeholder="Start Date" formcontrolname="date">
  <error [hidden]="myForm.controls['date'].valid || myForm.controls['date'].pristine" align="start">Start Date required</error>
</md-datetimepicker>
```
