# gitdemo
gitdemo 用於測試刪除某些不可描述的歷史

# commited wrong thing
- to update last commited description
    - git ci --amend
        - if you just commited wrong contant and no push to github
            - git push origin master
        - if you've already pushed to github
            - git push -f origin master
                - *there will be no history on github*
- to update any commited contant
    - git rebase -i <commit>~n [ ex:git rebase -i HEAD~4 ]
        - upated file contant
    - git rebase --continue
        