# Basics of n8n

## Nodes
To perform a task.



2 major types of nodes:

1. **trigger node - **The first node in workflow. It is mandatory node
2. **action node - **The followup nodes in the workflow. This is not a trigger node.


---

### Trigger Node
This node is from where your workflow starts



![image.png](https://eraser.imgix.net/workspaces/fgq5DbDNQLz2BKDWSKTx/0yDRqZMpHlMykPfk32FEwhZnFFC3/osedWoH2d0pNge5L5IP7G.png?ixlib=js-3.7.0 "image.png")

![image.png](https://eraser.imgix.net/workspaces/fgq5DbDNQLz2BKDWSKTx/0yDRqZMpHlMykPfk32FEwhZnFFC3/kIvM-QsHiII1uGrgWlbjX.png?ixlib=js-3.7.0 "image.png")



1. **Manual trigger** - When we manually click on the trigger. While testing workflows or during development.
2. **Integration triggers** - They work when something new happens in the app.
3. **Scheduled trigger** - This triggers the workflow on a set schedule
4. **Webhook trigger** - Starts on an event through HTTP alerts. When app trigger not available.
5. **On form Submission** - You create a custom form and trigger the workflow when the form is submitted
6. **Chat message trigger** - The input prompt is the output of the trigger. Starts when the chat is submitted.


---

### Action Nodes


![image.png](https://eraser.imgix.net/workspaces/fgq5DbDNQLz2BKDWSKTx/0yDRqZMpHlMykPfk32FEwhZnFFC3/huCV3Q_6YIoFKDvC3oLxT.png?ixlib=js-3.7.0 "image.png")



1. **AI Action node -** AI based nodes, LLM Nodes, Agentic Nodes.
2. **Action in an App -** Perform action in certain app.
3. **Data transformation Node -** You transform data.
4. **Flow Node -** Decide the flow of the workflow, Conditional nodes
5. **Core nodes -** Utility nodes. eg. Code Node
6. **Human in the Loop -** Wait for human approval to continue.


