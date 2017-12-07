# The-First-or-last-repository
From a lazy man with severe delusion.

  Eh..I'm a Chinese. And I think it'd be better to finish the first repository in English which can make me professionally to some extent...
  Well,in addition to be cool,another destination to use github is that I want to study Python systematically. I need a place to store,modify,manage and share my idea(code) with others(or just myself). Eh...I'm a lazy man and I often give up doing one thing because of various of reasons like too difficult,too boring,feeling there's no better prospect etc. But recently, as the popularity of AI(artificial intelligence) wider and wider, I'm appealed to the wonderful incredible computer language and I... WELL I JUST WANG TO HAVE THE SAME JOB LIKE OTHERS' WORKING ON AI SO THAT I CAN EARN A LOT OF MONEY.
  So,now you can regard me as a ostrich, an idiot has no endurance but still want to live a rich life...
  BUT,anyone can change. The key reason why a person resists doing sth to make him better is just the missing of his interest. Maybe I can find my interest this time, who knows?
  I'll persist to record the process of learning Python and some procedures on the github for somedays,maybe some months? 
  Bless me!
  
  WeifanWong created at 2017.12.07 6:53 pm
  
   刚才遵循GitHub官网上的教程完成了自己的第一个“repository”。目前我对GitHub工作原理的理解是：repository相当于一个存储数据的介质，其拥有最高等级的操作权限，最终数据的有效性都要以它为基准。而branch相当于一个地址，它可以看做指向repository副本的地址，或者可以将branch看作是一个指针，当它指向某一个版本的repository副本时，我们进行的modify都是基于该版本副本进行的，而不会影响到其他副本甚至repository主介质。
   其中最令我惊奇的是该例子中readme-edits分支（branch）与master（repository主介质）的比较部分，直观的看到了在该副本中我做的modify。不禁，如果在处理一个大project的时候，我们就不是基于主介质创建branch，而是基于自己（他人）先前就创建好的branch副本。这样我们就可以在commit change时在不影响主介质的前提下，将自己的修改保存在一个等级较低的副本中，非常安全。
   
   Take for an example 举个例子，之前我在master主介质的基础上建立了readme-edits副本分支，现在我又在readme-edits副本分支的基础上又建立了名为readme-edits #2 的branch。当我这次在最后Merge pull request的时候，就只会更改readme-edits副本。现在来验证我的猜想吧！
