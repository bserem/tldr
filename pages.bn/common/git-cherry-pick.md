# git cherry-pick

> বিদ্যমান কমিট দ্বারা প্রবর্তিত পরিবর্তনগুলি বর্তমান ব্র্যাঞ্চে প্রয়োগ করুন।
> অন্য ব্র্যাঞ্চে পরিবর্তনগুলি প্রয়োগ করতে, প্রথমে পছন্দসই ব্র্যাঞ্চে স্যুইচ করতে `git checkout` ব্যবহার করুন।
> আরও তথ্য পাবেন: <https://git-scm.com/docs/git-cherry-pick>।

- বর্তমান ব্র্যাঞ্চে কমিট করুন:

`git cherry-pick {{কমিট}}`

- বর্তমান ব্র্যাঞ্চে বিভিন্ন ধরনের কমিট করুন (এছাড়াও দেখুন 'git rebase --onto`):

`git cherry-pick {{শুরুর_কমিট}}~..{{শেষের_কমিট}}`

- বর্তমান ব্র্যাঞ্চে  একাধিক (অ-ক্রমিক) কমিট  করুন:

`git cherry-pick {{কমিট_১ কমিট_২ ...}}`

- কমিট তৈরি না করেই ওয়ার্কিং ডিরেক্টরিতে কমিটের পরিবর্তন যোগ করুন:

`git cherry-pick --no-commit {{কমিট}}`
