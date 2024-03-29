# How to pass the Linux Foundation CKAD exam
If you're interesting in passing the CKAD (Certified Kubernetes Application Developer) exam, I hope the following advice helps!
_________________
- **Take [this course](https://kodekloud.com/courses/certified-kubernetes-application-developer-ckad/)** unless you are already advanced with Kubernetes. I found this course significantly more helpful than other ones I took, including the official Linux Foundation CKAD course (which is a bit outdated and involves painful setup).
- **[Use kubectl commands](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands)**. There is not enough time during the exam to create/edit yaml files manually for each task, so get comfortable with running kubectl commands directly. Especially `kubectl edit pod`
- **Practice and get comfortable with yaml**. Although kubectl commands will save you time and effort, some tasks must be done by manually creating/editing yaml files (Persistent Volumes, Network Policies etc), so get comfortable and confident with the general format.
- **Practice and get comfortable with vim** unless you have a preferred editor that is supported.  If using vim, here is a [suggested `.vimrc` configuration](https://github.com/SWE-SUCCESS/SWE-SUCCESS/blob/main/CKAD/suggested.vimrc).
- **Bookmark Kubernetes documentation links**. At the very least, the official [kubectl docs](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands) and [kubectl cheatsheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) are must-haves. Check out a [comprehensive list](https://github.com/SWE-SUCCESS/SWE-SUCCESS/blob/main/CKAD/suggested_bookmarks.md) of suggested bookmarks.
- **Complete tasks by knowledge and value**. There will likely be 15-20 tasks on the exam that are worth different numbers of points and vary in difficulty depending on your strengths and weaknesses. Although you should definitely attempt every task, focus first on simple and valuable ones rather than working through them sequentially. Make note of skipped tasks and revisit them at the end rather than getting stuck on a single one.
- **Remember namespaces**. Ensure you are working in the correct namespace for each task (it will be clear in the instructions). Include `-A` or `--all-namespaces` in kubectl commands to view resources across every namespace.
- **Copy and Paste**. Do not waste time/brain cells/possibly typing incorrect names for resources.  Copy and Paste resource names directly from the instructions.
- **Use resource shortnames**. This will save a little bit of time in typing, but more importantly help prevent typos or the need to lookup the full name of a given resource. Check out some of the most important [shortnames](https://github.com/SWE-SUCCESS/SWE-SUCCESS/blob/main/CKAD/kubectl_shortnames.md)

Unsure if the CKAD exam is right for you? Check out [Is the Linux Foundation CKAD exam worth taking?](https://github.com/SWE-SUCCESS/SWE-SUCCESS/blob/main/CKAD/is_ckad_exam_worth_taking.md)
_________________
If this post helped you please let me know :smile: or
[<div><img src="https://user-images.githubusercontent.com/108257462/179425081-177b3f47-fe38-4bd3-86db-a0b6169deb23.png" width="200" height="50"></div>](https://www.buymeacoffee.com/cmliotta)
