# Building LLM application

https://www.deeplearning.ai/the-batch/issue-294/

First, while fine-tuning is an important and valuable technique, many teams that are currently using it probably could get good results with simpler approaches, such as prompting (including writing mega prompts), few-shot prompting, or simple agentic workflows.


https://www.deeplearning.ai/the-batch/from-prompts-to-mega-prompts/?utm_campaign=The%20Batch&utm_medium=email&_hsenc=p2ANqtz-_ZSXRCYtNKbdkb1OTRDF24ySlHj3jlGYwLRTcmlCS1i7U6840Ws0bgp3iPx45M1_ZOmN5U6mHxBHLfMcSZmt-zuK0U4A&_hsmi=353823758&utm_content=353823758&utm_source=hs_email:

When building complex workflows, I see developers getting good results with this process:

- Write quick, simple prompts and see how it does.
- Based on where the output falls short, flesh out the prompt iteratively. This often leads to a longer, more detailed, prompt, perhaps even a mega-prompt.
- If that’s still insufficient, consider few-shot or many-shot learning (if applicable) or, less frequently, fine-tuning.
- If that still doesn’t yield the results you need, break down the task into subtasks and apply an agentic workflow.

I hope a process like this will help you build applications more easily. If you’re interested in taking a deeper dive into prompting strategies, I recommend the Medprompt paper, which lays out a complex set of prompting strategies that can lead to very good results.

https://arxiv.org/abs/2311.16452?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-9KTqJYw8uJZw37gIcadWEifUEAY1kRzzf5aaShK5nAYEb1Or4KdseKy3s6Q_dyLgXQYnJE



