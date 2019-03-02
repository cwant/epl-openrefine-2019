---
title: "Sorting data with OpenRefine"
teaching: 10
exercises: 10
questions:
- "How can we sort our data?"
objectives:
- "Sort table by a column."
- "Sort by multiple columns."
keypoints:
- "OpenRefine provides a way to sort data without affecting the raw data."
- "Multiple sort criteria can be used"
---

## Sorting

You can sort the data by a column by using the drop-down menu in that column.
There you can sort by `text`, `numbers`, `dates` or `booleans` (`TRUE` or `FALSE` values).
You can also specify what order to put `Blanks` and `Errors` in the sorted results.

If this is your first time sorting this table, then the drop-down menu for the
selected column shows `Sort...`. Select what you would like to sort by
(such as `numbers`). Additional options will then appear for you to fine-tune your sorting.

> ## Exercise
>
> Sort the data by `Branch Name`.
>
> > ## Solution
> > In the `Branch Name` column, select `Sort...` > `Text`
> > and select `a-z`.
> {: .solution}
{: .challenge}

Note also that a `Sort` menu has appeared above the data.
This provides a summary of the sorts that are being performed
on the data, as well as some controls to manipulate the
currently activated sorts.

If you try to re-sort a column that you have already used,
the drop-down menu changes slightly, to > `Sort` without the `...`,
to remind you that you have already used this column.
It will give you additional options:

* `Sort` > `Sort...` - This option enables you to modify your original sort.
* `Sort` > `Reverse` - This option allows you to reverse the order of the sort.
* `Sort` > `Remove sort` - This option allows you to undo your sort.

### Sorting by multiple columns.

You can sort by multiple columns by performing sort on additional columns.
The sort will depend on the order in which you select columns to sort.
To restart the sorting process with a particular column, check the
`sort by this column alone` box in the `Sort` pop-up menu.

If you go back to one of the already sorted columns and select > `Sort` > `Remove sort`,
that column is removed from your multiple sort. If it is the only column sorted,
then data reverts to its original order.

> ## Exercise
>
> With the branch name sort in place as above, add an additional sort to the
> date column
> (sorting as dates, earliest first).
>
> What was the fifth most requested book from people whose home branch is
> `Abbottsfield - Penny McKee` for
> the week ending on July 10, 2017? How many times was it requested?
> > ## Solution
> >
> > Add another sort on the `Number of Holds` column, sorting as `numbers` in
> > reverse order.
> >
> > The answer is `The spooky cabin / based on the teleplay Pups and the ghost
> > cabin by Scott Albert ; illustrated by Jason Fruchter` with `20` holds.
> {: .solution}  
{: .challenge}

{% include links.md %}
