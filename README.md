### ilm-job-quest

Hi all developer! Welcome to Index Living Mall. Being a developer at Index Living Mall is challenging so we have challenges for you! These challenges are designed to assess your learning skill, which is the fundamental and most important skill of a great software developer. So I do not expect you to have full or any knowledge about the topic beforehand but it's your job to try to learn and answer those challenges.

## Algorithm in Javascript
Code must be written in Javascript language. The code will be tested with Node8, so you can use all Javascript features that are available in Node8.

1. Write a function that swap the elements of array from n index to n index and replace the elements of array from n index to n index. the function receives 4 parameters, 1st is an array, 2nd is the operation ('swap' or 'replace'), 3rd is the number of elements which will be operate, 4th is the number of elements which will be operated. For example,

```
> shift(['john', 'jane', 'sarah', 'alex'], 'swap', 1,3)
['john', 'alex', 'sarah', 'jane']

> shift([100, 234, 374, 498 ,511], 'replace', 3,0)
[498, 234, 374, 498 ,511]
```

2. Download [work-weekly.json](https://github.com/indexlivingmall/ilm-job-quest/blob/master/work-weekly.json) and write a code to calculate these values from **work-weekly.json**
- 2.1 Average **working time** of all employee this week
- 2.2 Average **Start time** for employee that has 'officer' as **position** this week
- 2.3 Find the employee who got the most **working time** this week
- 2.4 Find the employee who came late. The answer must be include dateTime 
    * remark 2.4
    - start work at 8.30 am.
    - result list => 
    ```
        output = [{
            name: "XX1",
            dateTime: [
                {
                    date: "2019-05-08",
                    time: "08.31"
                },
                {
                    date: "2019-05-04",
                    time: "09.12"
                }
            ]
        },
        {
            name: "XX2",
            dateTime: [
                {
                    date: "2019-05-08",
                    time: "08.34"
                }
            ]
        }]
    ```