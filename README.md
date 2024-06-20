# CalendarWeekMonthSwitch
Calendar Week Month Switch  vue3 日历组件周月切换

![CPT2406201706-695x599](https://github.com/totome911/CalendarWeekMonthSwitch/assets/12454336/0a8d4873-ae7c-4a13-b75e-7b78e45a52ee)

可以切换周模式和月模式,依赖于 dayjs 和vue3
```
   <Calendar  @select="select" />
    import Calendar from '@/components/Calendar.vue'
      select: (date) => {
            console.log(date);
        },

```
