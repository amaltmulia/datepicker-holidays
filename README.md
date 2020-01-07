# datepicker-holidays
A little modification from [bootstrap-datepicker](https://github.com/uxsolutions/bootstrap-datepicker) by uxsolutions

### Requirements
1. [Bootstrap](https://getbootstrap.com/) 2.0.4+
2. [jQuery](https://jquery.com/) 1.7.1+

### How to Use
Call the datepicker via javascript, with additional parameters ```showHoliday```, ```datesHoliday```, and ```holidayNames```
```showHoliday``` is boolean (true/false)
```datesHoliday``` is the collection of holiday date, date type
```holidayNames``` is the collection of holiday name, string type (based on datesHoliday)

For Example :
~~~javascript
$('.datepicker').datepicker({
    showHoliday: true,
    datesHoliday: ['12/31/2019','01/01/2020'],
    holidayNames: ['New Years Eve','New Year']
});
~~~