### Hello, welcome to my personal repositorie.  👋

<!--
**glaucius/glaucius** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=glaucius&show_icons=true&hide_border=true&&count_private=true&include_all_commits=true" />

### My .bahsrc color stuff and git branch on spotlight, helps us to take care !!

Just add it into your .bashrc file.

```
parse_git_branch() {
     git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/(\1)/'
}

export PS1="\e[36m\u@\h \[\e[32m\]\w \[\e[93m\]\$(parse_git_branch)\[\e[00m\]$ "
```


