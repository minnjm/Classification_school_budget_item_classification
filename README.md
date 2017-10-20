Summary:

Budgets for schools and school districts are huge, complex, and unwieldy. It's no easy task to digest where and how schools are using their resources. Education Resource Strategies is a non-profit that tackles just this task with the goal of letting districts be smarter, more strategic, and more effective in their spending.

Your task is a multi-class-multi-label classification problem with the goal of attaching canonical labels to the freeform text in budget line items. These labels let ERS understand how schools are spending money and tailor their strategy recommendations to improve outcomes for students, teachers, and administrators.


The metric used for this competition is affectionately named 'multi-multi'. In this competition we have multiple dependent variables, and each of these variables can take on one of multiple labels. So, multiple dependent variables, multiple labels in each, multi-multi-class-log loss. In this calculation, KK is the number of dependent variables, NN is the number of rows being evaluated, and CC is the number of class values kk can take on. As a note, if your probabilities don't sum to 1 for each class, we will normalize them for you. The goal is to minimize multi-multiclass log loss.
