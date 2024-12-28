# Azure Resource Management and Cost Monitoring Automation

This repository provides guidance and resources for managing Azure resources and monitoring costs by creating automation tasks. By leveraging Azure Automation tasks and Logic Apps, you can automate repetitive tasks, optimize cost management, and enhance operational efficiency in your Azure environment.

## Features

- **Automated Cost Monitoring**: Send weekly or monthly cost updates for your resources.
- **Customizable Automation Workflows**: Create, configure, and manage workflows to suit your specific requirements.
- **Task Run History**: Monitor task execution history, including run statuses, durations, and step-level details.
- **Workflow Updates**: Easily edit and clone existing workflows for continuous improvement.
- **Export and Share Templates**: Export workflows to reusable JSON templates for consistent automation practices.

## Getting Started

### Create an Automation Task

1. Navigate to the **Automation** section of your Azure resource's menu and select **Tasks (preview)**.
   <br />
    <br />
     <img src="https://imgur.com/E375Z3X.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
     <img src="https://imgur.com/SOc75Da.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
2. On the **Tasks** pane, click **Add a task** and select a task template.
     <br />
    <br />
     <img src="https://imgur.com/J15oK1Y.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
3. Under **Authenticate**, provide credentials for the connections required by the task.
     <br />
    <br />
     <img src="https://imgur.com/HgvHqt0.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
4. Configure the task by providing a name and additional details, then click **Review + create**.
     <br />
    <br />
     <img src="https://imgur.com/mX9VRvd.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
5. The created task will appear in the Tasks list and run automatically.
    <br />
    <br />
     <img src="https://imgur.com/J8aTvfG.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />

### Monitor Task Runs

- View task run history, including statuses, start times, and durations, from the **Runs history** pane.
     <br />
    <br />
     <img src="https://imgur.com/oufu1Nk.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
- Select a specific run to view detailed information about each workflow step, including inputs, outputs, and execution duration.
 <br />
    <br />
     <img src="https://imgur.com/hKM9xYc.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />

### Update an Automation Task

1. Find the task in the **Tasks** list, open its ellipses menu, and select **Edit in-line**.
    <br />
    <br />
     <img src="https://imgur.com/JTqRqze.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
2. Update authentication credentials, task properties, or email addresses as needed.
    <br />
    <br />
     <img src="https://imgur.com/2VEFYOs.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
3. For advanced edits, open the task in **Logic Apps** and use the designer to modify workflows.
    <br />
    <br />
     <img src="https://imgur.com/5aFWZ0i.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />

### Clone and Edit Workflows

1. Open the workflow in Logic Apps, navigate to the **Overview** pane, and select **Clone**.
    <br />
    <br />
     <img src="https://imgur.com/isMoexd.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
2. Name the cloned workflow and set its status to **Disabled** for safe editing.
    <br />
    <br />
     <img src="https://imgur.com/D1kFMRk.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
3. Modify triggers, actions, and properties, then save and test your changes.
    <br />
    <br />
     <img src="https://imgur.com/4KLCxmv.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />

### Export Automation Task Templates

1. Open the logic app workflow in the Azure portal.
    <br />
    <br />
     <img src="https://imgur.com/wo3XpZA.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
2. Navigate to the **Overview** pane and select **Export > Export to Automation Task**.
    <br />
    <br />
     <img src="https://imgur.com/gdxAcGd.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
5. Provide template details and save the file with the `.json` extension using a consistent naming convention (e.g., `list-stale-virtual-machines.json`).

## Best Practices

- Use recurring or event-based triggers for workflows.
- Clone workflows before making changes to ensure uninterrupted operations.
- Use descriptive names for tasks and templates to maintain clarity.


---

Start automating your Azure resource management and cost monitoring tasks today!
