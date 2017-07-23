# TOP NZ CLOTHING FACEBOOK PAGE ANALYSIS

List of top brands obtained from https://theculturetrip.com/pacific/new-zealand/articles/top-10-new-zealand-fashion-designers-you-should-know/

Among these 10 brands random 3 brands are analysed to answer the following questions:

- How many people are engaging with these brands?
    - For each brand we will extract the number of reactions (which includes 'likes') shares comments given in each post. Then compare these data with other brands.
    - We also need to measure how many percentage of the total fans for these brands are engaging in these posts. This relative data is measured upon diving previous step data with total fans in each page.

- What kind of posts are been shared in these brands?
    - For each brand we will first extract messages from each posts then analyse frequency of words in these messages finally identify the top N words that will summarize the type of message been shared with people.

- How frequent and at what time these posts are created by these brands?
    - We will extract the post creation time which will be in `%Y-%M-%D %H:%M:%S` format. Then from each post `%Y-%M-%D` will be used to find post frequency and `%H` will be used to find the time at which these posts are created.
