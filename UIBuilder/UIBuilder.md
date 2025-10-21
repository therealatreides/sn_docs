
# Zurich Build or modify applications


Last updated: October 16, 2025


Some examples and graphics depicted herein are provided for
illustration only. No real association or connection to ServiceNow
products or services is intended or should be inferred.


[This PDF was created from content on docs.servicenow.com. The web](http://docs.servicenow.com/)
site is updated frequently. For the most current ServiceNow product
[documentation, go to docs.servicenow.com.](http://docs.servicenow.com/)


**Company Headquarters**

2225 Lawson Lane

Santa Clara, CA 95054

United States

(408)501-8550


## **UI Builder**


UI Builder is a web user interface builder. Use UI Builder to build pages for
App Engine Studio generated workspaces or custom web experiences
using Next Experience Components and custom web components.


**UI Builder overview**


Create or customize pages for workspace experiences. A page is a
collection of components that make up a workspace user interface.


Create variants of pages to target experiences for different audiences.
For example, you can create a home page for agents, and a variant for
managers at the same URL.


**Note:** The ui_builder_admin role is required to complete tasks in UI
Builder.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-3-1.png)


Use the UI Builder library of components to build your pages. Configure
them any way that you need and then connect your organization's data
to the components.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-4-1.png)

**Get started with UI Builder**

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-4-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-5-2.png)

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-5-3.png)


**Note:** UI Builder isn't yet capable of building or configuring
ServiceNow base system service portals, such as the Employee
[Center. For service portals, continue to use the Service Portal](https://www.servicenow.com/docs/csh?topicname=t_ConfigureAPage&version=zurich&pubname=zurich-platform-user-interface)
[Designer.](https://www.servicenow.com/docs/csh?topicname=t_ConfigureAPage&version=zurich&pubname=zurich-platform-user-interface)


**Troubleshoot and get help with UI Builder**


**•** Contact your company's Customer Admin to unlock or add user
accounts, perform restores or zBoots, and more.


**•** [Ask or answer questions in the UI Builder community](https://www.servicenow.com/community/next-experience/ct-p/next-experience)


**•** [Search the Known Error Portal for known error articles](https://support.servicenow.com/kb?id=kb_article_view&sysparm_article=KB0597477)


**•** [Learn more about how to create your own apps on the developer site.](https://developer.servicenow.com/dev.do#!/)


**•** [Contact Customer Service and Support](https://support.servicenow.com/now?draw=case)


**•** Exploring UI Builder


Explore facets of UI Builder to set you up for creating pages quickly.


**•** Learning UI Builder


Learn how to navigate the UI Builder and explore some common use
cases to learn by example.


**•** Working in UI Builder


Get a full understanding of everything that you can do when creating
a page for your workspace or custom portal experience in UI Builder.


**•** Advanced UI Builder


UI Builder can be used by application developers with a variety of
skill levels. We recommend developers with a high level of experience,
sometimes referred to as pro-coders, perform the procedures in this
section.


**•** Component Builder


Learn how to use Component Builder to assemble reusable
components for your UI Builder pages.

## **Exploring UI Builder**


Explore facets of UI Builder to set you up for creating pages quickly.


UI Builder is a web user interface builder. Use UI Builder to build
pages for CSM Configurable Workspace, App Engine Studio generated
workspaces and portals, or custom web experiences using Next
Experience Components and custom web components.


Check out the UI Builder quick start topic to understand the basics of UI
Builder. If you want a deeper understanding of UI Builder, go through the
tutorial to learn how to create your first page.


Find information relating to UI Builder audiences, security and roles
settings like application scope and domain separation, as well as
experience settings.


See how you can use UI Builder with CSM Workspace and portal
experiences.


**•** UI Builder quick start


This quick start guides you through the process of creating your
first page in UI Builder. Creating your first page is the first step in
understanding how to build user interface pages for your workspace
or custom portal experiences.


**•** UI Builder tutorial


Learn how to use the basics of UI Builder to create a page called My
Tutorial.


**•** UI Builder and configurable workspaces


Use UI Builder to create pages for your configurable workspace
experiences.


**•** Experience settings for UI Builder


Learn about the UI Builder experience settings to build your own
workspace and custom portal experiences.


**•** Helpful resources for UI Builder


Some ServiceNow resources that can provide you with helpful
information.


**•** UI Builder glossary


Learn about the terms and concepts used in UI Builder (UIB).

## UI Builder quick start


This quick start guides you through the process of creating your first page
in UI Builder. Creating your first page is the first step in understanding
how to build user interface pages for your workspace or custom portal
experiences.


**Before you begin**


Role required: ui_builder_admin


In this UI Builder quick start, you perform the following tasks to build your
first page in UI Builder:


**•** Start UI Builder.


**•** Create a page for your workspace or custom portal experience. For
more information about creating pages, see Create a page in UI
Builder.


**•** Build your page by adding components. For more information about
components, see Customize UI Builder pages using components.


**•** Save your page.


**•** Preview your page to see how it looks in a browser.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .
Start UI Builder

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-8-1.png)


2. Select an experience that you want to work in from the UI Builder
home page.
If you don’t see any experiences listed in which to work, contact
your administrator to get access to an experience, or create an


experience. For more information, see Configure how users interact
with your applications in UI Builder.


3. Create a page.


a. Select the **+** icon in the **Pages and variants** section.


b. Select **Create a new page** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-9-1.png)


c. Select **→ Create from scratch instead** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-10-1.png)


You can also create pages using page templates, see Create a
page from a template for more information.


d. Enter `Start Page` as the unique name for the page in the **Name**
field.


e. Specify a path for your page in the **URL Path** field. UI Builder
generates a default path based on the name that you gave in
the last step.
A default path is added based on your page name. You can
also create your own path. The path is required and must be
unique. The path can include digits (0-9), letters (A-Z, a-z), and
a few special characters ( `"-"`, `"."`, `"_"`, `"~"` ), with the words


separated by a forward slash or hyphen. The **URL preview** shows
the path of your page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-11-1.png)


**Note:** The application scope defaults to the scope that
the user is currently in within the ServiceNow AI Platform®.
For more information about the application scope, see Learn
about security and roles.


f. Select **Continue** .


g. (Optional) Add parameters to your page URL by selecting **+ Add** .
For more information, see Manage UI Builder pages and page
variants.


h. Select **Looks good** .


i. Enter `Manager Start Page` as the name for the page variant.


j. (Optional) Add one or more audiences for this page.
If an audience you need isn’t listed, you can choose the **Open**
**audiences in the platform** link to create one.


k. (Optional) Add conditions for when to display the page or tab.


l. Select **Continue** .


m. On the next screen, select **Build responsive** .


n. Select **Create** to create your blank page.
Congratulations! You’ve created your first page! The page is empty
of content. You add components to the page to build functionality
to it. Components are the building blocks of a page. UI Builder
comes with many components ready for you to add to your page.
Components can be as simple as a **Heading**, or as complex as a **List** .


4. Select **Editor** to start adding customizing your page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-12-1.png)


5. Add a container component to your page.
A container is what holds your components. Think of a container
as an area of the page where you add information, images, or
functionality (your components). You can have as many containers
on a page as you want, with as many containers within containers,
with as many components in the containers.


a. Select **+ Add content** in the content tree.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-13-1.png)


b. Select the **Single column** layout in the toolbox.


c. Select **Column layout 1** in the content tree to highlight the
container.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-13-2.png)


d. Select the component name in the configuration panel.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-14-1.png)


e. In the **Component label** field, type `Container for heading` .


f. In the Component ID field, type `container_for_heading` .


g. Select **Apply** .


See that the column layout name changes to **Container for**
**heading** in the content tree. The content tree is an important
concept. The content tree is an easy way to see the structured
layout of your page. The content tree is especially important
when you have multiple components on your page. You select
the component in your content tree to highlight the component
on the page, making it easier to build your page. You can do a
text search for a component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-15-1.png)


For more information on component IDs, see Component ID.


You’ve successfully added your first column layout to your page.


6. Add a **Heading** component to your column layout.
You can add components to the page in different ways. For more
information on the ways you can add components to your page, see
Add and configure components.


a. Select **+ Add content** in the content tree below the column
layout created in step 5.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-16-1.png)


b. Type `heading` into the search and select the **Heading**
component.


c. Select your new **Heading** component in the content tree to
highlight it.


d. Select **None** in the configuration panel.


e. Select the component name in the configuration panel.


f. In the **Component label** field, enter `Custom heading` as the
unique label for the heading component.


g. In the **Component ID** field, enter `custom_heading` as the unique
ID for the heading component.


h. Click **Apply** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-17-1.png)


7. Customize the heading component.


a. Select the heading component in the content tree.


b. Select the **Configure** tab in the configuration panel.


c. In the **Label** field, enter the text of your heading, such as `My new`
`heading` .


d. The Style changes the size of the heading text.
For example, if you select **Header-secondary**, the text is smaller.
Different headings sizes are useful if you have two headings
and want the second heading smaller that the primary heading.
For more information on configuring components, see Configure
components in UI Builder.


e. Leave the **Level** as **1** .


f. Select **Save** .
You’ve added and customized a heading component to your page.


8. Add a second column layout to your page.


a. Similar to before, select **+ Add content** in the content tree.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-18-1.png)


b. Select the **Single column** layout in the toolbox.


c. Select **Column layout 1** in the content tree to highlight the
container.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-19-1.png)


d. Select the component name in the configuration panel.


e. In the **Component label** field, type `Container for content` .


f. In the **Component ID** field, type `container_for_content` .


g. Select **Apply** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-20-1.png)


h. Select **Save** .
You’ve successfully added your second container component to

your page.


9. Add an image component to your page.
An image is a nice way to add a visual for your page. In this quick
start, you add a stock photo that comes with UI Builder. But you can
add any image that is available to you.


a. Select **+ Add content** in the content tree below the container
created in step 8.


b. Type `image` into the search and select the **Image** component.
A default image is loaded in the image component. You can
add your own image by adding a URL to the image. You can
use images hosted on the internet or images in the ServiceNow
AI Platform®. If you use an image hosted on an external site, you
must use the `https` protocol for security.


c. Select the **Image 1** component in the **Content** tree to highlight
the image.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-21-1.png)


d. Select **None** in the configuration panel.


e. Select the component name in the configuration panel.


f. In the **Component label** field, type `My image` .


g. In the **Component ID** field, type `my_image` .


h. Select **Apply** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-22-1.png)


i. Select **Save** .
You added an image component to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-23-1.png)


10. Select **Preview** in the UI Builder header to preview your page.
Congratulations! You completed the UI Builder quick start. Your page
generates a preview of how it looks in your Workspace or portal
experience.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-24-1.png)


**Result**


1. Created your first page in UI Builder.


2. Added your first container component to the page. You changed
the label for the container.


3. Added a **Heading** component as a title to the container. You
changed the text of the heading. You also changed the label.


4. Added a second container component to your page. You changed
the label for the container.


5. Added an **Image** component. You changed the label of the image
component.


6. Saved your new page.


7. Previewed your page in the browser.


You successfully completed the UI Builder quick start!

## UI Builder tutorial


Learn how to use the basics of UI Builder to create a page called My
Tutorial.


**Before you begin**


Role required: ui_builder_admin


In this UI Builder tutorial, you perform the following tasks to build a page in
UI Builder:


**•** Start UI Builder.


**•** Create a page for your workspace or custom portal experience. For
more information about creating pages, see Create a page in UI
Builder.


**•** Change the layout of the page to have two columns. For more
information, see Organize components in UI Builder pages.


**•** Build your page by adding two container components.


**•** Rename your container components in the content tree.


**•** Add a **Heading** component and a **Button** component to the first
container. Add a **data visualization component** to the second
container. For more information about components, see Customize UI
Builder pages using components.


**•** Configure your components as follows:


**•** Link the button to the ServiceNow® website.


**•** Connect the **Data visualization** component to a data source to
display task data. For more information about data resources, see
Dynamically expose data in UI Builder pages (advanced feature).


**•** Save your page often.


**•** Preview your page to see how it looks in a browser.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .
You can also type `UI Builder` directly in the **Filter navigator** .
Start UI Builder

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-26-1.png)


2. From the UI Builder home page, choose an experience you want to
work in.
If you don’t see any experiences listed in which to work, contact
your administrator to get access to an experience or create an
experience. For more information, see Configure how users interact
with your applications in UI Builder.


3. Create a page.

|To do this task|Do the following|
|---|---|
|Create a page|a. Select the**+** icon in the**Pages and**<br>**variants** section.<br>b. Select**Create a new page**.|


|To do this task|Do the following|
|---|---|
||c. Select**Create from scratch instead**.<br>d. Enter the name of your new page.<br>The name can be anything you want.<br>In this example, you can type`My`<br>`tutorial page`.<br>e. In the**Path** field, a path is<br>automatically entered based on your<br>page name. In this example, the Path<br>is`my-tutorial-page`. The path is the<br>URL of the page. You can change this<br>path to anything you want, but the<br>path must be unique. The path has to<br>be lowercase and contain no spaces.<br>The**URL preview** shows what the path<br>of your page will be.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-27-1.png)


|To do this task|Do the following|
|---|---|
||f. Select**Continue**.<br>g. (Optional) Add parameters to your<br>page URL.<br>h. Select**Looks good**.<br>i. Enter the name of your page variant.<br>The name can be anything you want.<br>In this example, you can type`My frst`<br>`page variant`.<br>j. Add an audience for the page variant<br>by selecting**+ Add an audience**. In this<br>example, select**Admin**.<br>k. Select**Continue**.<br>l. On the next screen, select**Build**<br>**responsive**.<br>m. Select**Create**.<br>n. After your page is created, the<br>page editor screen appears. You|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-28-1.png)


|To do this task|Do the following|
|---|---|
||can change advanced settings such<br>as the**URL settings** and**Variant**<br>settings. For this tutorial, you can skip<br>these advanced options. For more<br>information on changing advanced<br>settings, seeCreate a UI Builder page:<br>Advanced settings.<br>UI Builder Page Editor<br>|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-29-1.png)


Congratulations! You created your tutorial page! The page is empty
of content. You add components to the page to build functionality
to it. Components are the building blocks of a page. UI Builder
comes with many components ready for you to add to your page.
Components can be as simple as a **Heading**, or as complex as a **List** .


4. Change the layout of the page to a two-column layout.


For more information about layouts, see Organize components in UI
Builder pages.


|To do this task|Do the following|
|---|---|
|Change the layout<br>of the page to two<br>columns|a. Select the**Body** level of the**Content**<br>tree to highlight the page.<br>b. Select**+ Add content** in the content<br>tree.<br>c. Select the**Two columns** layout.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-30-1.png)


|To do this task|Do the following|
|---|---|
||d. Select**Add**.<br>e. The two column layout appears.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-31-1.png)


|To do this task|Do the following|
|---|---|
|||


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-32-1.png)


5. Add a **Heading** component, and a **Button** component to the left
column.


|To do this task|Do the following|
|---|---|
|Add a heading<br>component to your<br>left-column container|You can add components to the page in<br>different ways. For more information on the<br>ways you can add components to your<br>page, seeTable 1.<br>a. Select the**+** button in the middle of<br>the left column.<br>b. Type`Heading` in the search field.|


|To do this task|Do the following|
|---|---|
||c. Select the**Heading** component to<br>add it to your container. A heading<br>component is a way to add text or a<br>title to your page.<br>d. Select**Add**.<br>e. Select the component name in<br>the configuration panel to see the<br>**Component label** and**Component ID**.<br>You can change these to anything<br>you want, as long as they’re unique.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-33-1.png)


|To do this task|Do the following|
|---|---|
||f. Select**Apply**.<br>g. Configure your**Heading** component.<br>Component authors configure<br>components to expose the<br>appropriate properties required to set<br>up their components.<br>**•** Set the style to**Header-primary**.<br>The Style changes the class of<br>the heading text, like font, weight,<br>and color. For example, if you<br>select**Header-secondary**, the text<br>is smaller. Different headings sizes<br>are useful if you have two<br>headings and want the second<br>heading smaller that the primary<br>heading.<br>**•** Enter`My Tutorial` as the<br>heading text in the**Label** field.<br>**•** Leave the Level as**1**.|


|To do this task|Do the following|
|---|---|
|||
|Add and configure<br>a button component<br>to your left-column<br>container|Add a**Button** component to your page.<br>Configure the button by changing the<br>text and the way that it looks. Then<br>change what happens when you click<br>the button by adding an event handler<br>for the button. The event handler adds<br>an action to the button to link to the<br>ServiceNow® home page. So when you<br>click the button, the ServiceNow® home<br>page opens in a new tab of your browser.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-35-1.png)


|To do this task|Do the following|
|---|---|
||For more information about configuring<br>components, seeComponents.<br>a. Select the**+** on the bottom edge<br>of the heading component that we<br>added in the previous section.<br>b. Type`Button` in the search field.<br>c. Select the**Button** component in the list.<br>For more information on adding<br>components to your page, seeTable<br>1.<br>d. Select the component name in<br>the configuration panel to see the<br>**Component label** and**Component ID**.<br>You can change these to anything<br>you want, as long as they’re unique.<br>e. Configure the button component as<br>follows.<br>**•** Enter`Home Page` in the Label<br>field to change the name of your<br>button.<br>**•** Change the Size to**Large**.<br>**•** Enter`home` in the**Icon** search field.<br>**•** Select**Home Outline**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-36-1.png)


|To do this task|Do the following|
|---|---|
||f. Add an event handler to configure<br>what action applies to the button.<br>**•** Select the**Events** tab in the<br>configuration panel.<br>**•** Under Button clicked, select**+ Add**<br>**a new event handler**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-37-1.png)


|To do this task|Do the following|
|---|---|
||**•** Under Inherited event handlers,<br>select**Link to destination**.<br>**•** Click**Select destination**.<br>**•** In the**Select destination** screen,<br>select**External URL**.<br>**•** Type your URL. For this tutorial, type<br>`https://www.servicenow.com`<br>Select**OK**.<br>**•** Select**Add**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-38-1.png)

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-38-2.png)


|To do this task|Do the following|
|---|---|
||For more information about event<br>handlers, seeManage actions in UI<br>Builder pages.<br>g. Select**Save**. It is always a good idea to<br>save your page often as you work.<br>h. Select**Preview**.<br>i. Test the button you created in the<br>previous steps.<br>|


You added and configured the **Heading** and **Button** component for

your page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-39-1.png)


6. Add a **Data visualization** component to the container.


A data visualization component contains data that you display
in a visual manner. Configure the data visualization component
parameters. Then, add a data resource to it.


|To do this task|Do the following|
|---|---|
|Add and configure<br>a data visualization<br>component to<br>your right-column<br>container|You can add components to the page in<br>different ways. For more information on the<br>ways you can add components to your<br>page, seeTable 1.<br>a. Select the**+** button in the middle of<br>the right column.<br>b. In the**Search** field, start typing`Data`<br>`visualization` until you see the**Data**<br>**visualization** component, then select<br>the component to add it to your<br>page.<br>c. Select the component name in<br>the configuration panel to see the<br>**Component label** and**Component ID**.<br>You can change these to anything<br>you want, as long as they’re unique.<br>d. Add a data resource to your data<br>visualization component to bring in<br>customer account data.<br>**•** Select the data visualization<br>component, then select the<br>**Configure** tab.<br>**•** Select**Add data source**.<br>**•** Type`Task [task]` in the search<br>field and look for a task that<br>is available on your UI Builder<br>instance.<br>**•** Select**Add this source**.|


|To do this task|Do the following|
|---|---|
||e. Select**Data visualization type** drop-<br>down and select**Dial**. You can choose<br>a variety of visualization types to best<br>suit your data.<br>f. Select**Header and border** in the<br>configuration panel.<br>g. Enter`My Tasks` in the**Chart title** field.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-41-1.png)


|To do this task|Do the following|
|---|---|
|||


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-42-1.png)


You’ve added a **Data visualization** component to the right column
and configured it. You also added a data resource to bring in
customer account data.


7. Save the new page one last time.

|To do this task|Do the following|
|---|---|
|Save your page|a. In the far right corner of UI Builder,<br>select**Save**.<br>b. Now that you saved your page, you<br>can access it in your experience at<br>any time.|


8. Now preview your page to see what it looks like in a browser.

|To do this task|Do the following|
|---|---|
|Preview your page<br>|a. Select**Preview** in the UI Builder header.<br>b. See the heading in the left column of<br>your page.<br>c. Select the**Home Page** button. The<br>ServiceNow® home page opens in<br>another browser tab. Close the<br>browser tab to go back to your<br>preview page.<br>d. See the customer account data<br>visualization in the right column of your<br>page.<br>Preview your tutorial page<br>|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-43-1.png)


Congratulations! You completed the UI Builder tutorial.


**Result**


1. Created a page in UI Builder.


2. Changed the layout of your page to have two columns.


3. Added a **Heading** component as a title to your left column.


**•** Changed the text of the heading.


**•** Changed the label of the heading.


4. Added a button component below your heading component.


**•** Configured your button.


**•** Added an event handler for your button.


**•** Added an event handler to set up a link to a web page. When
you click the button, it opens the web page.


5. Changed the label for the right column.


6. Added a **Data visualization** component.


**•** Configured the data visualization component.


**•** Added a data resource to bring in task data.


7. Saved your new page.


8. Previewed your page.

## UI Builder and configurable workspaces


Use UI Builder to create pages for your configurable workspace
experiences.


A workspace is a collection of tasks and workflows in a single focused
working area that enables a user to efficiently complete an entire job.
It includes tools that a user can employ to quickly and easily assist
customers and resolve questions and issues. A workspace also includes
features that enable a user to be more efficient, including a multi-tab
interface for managing multiple cases and a contextual display that
provides quick orientation to the current task.


You can use UI Builder to create pages for your workspace experience.
UI Builder provides base system components that you can use to build
workspace pages.


To create a page in UI Builder for a Workspace experience, you navigate
to **All > Now experience framework > UI Builder** to open UI Builder.


The UI Builder home displays your available experiences under the
**Experiences** tab. If you are working in a Workspace experience, you
should see the experience listed here.


UI Builder home

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-45-1.png)


## Experience settings for UI Builder


Learn about the UI Builder experience settings to build your own
workspace and custom portal experiences.


By changing the settings of the workspace or portal experience that
you're working in, you can affect how your users interact with the
experience, how the experience looks, and how users navigate to and
from the experience.


Before you can edit the experience settings, you must be in the
correct application scope. If you're in a different scope, the experience
settings are read-only. To change your application scope, go to the


main header, select the application picker ( ), and then select
the application scope that you want. For more information about the
application scope, see Learn about security and roles.


**Workspace experience settings**


You can change these settings for your workspace experience:


**•** Modify or add some general settings for your experience. For example,
you can change the title, description, and the path of the workspace
or portal.


**•** Apply your organization's branding to all pages in your experience or to
a page within your experience.


**•** Configure your side navigation settings to add pages to the side
navigation in your experience.


**•** Turn on or turn off the notifications for your experience.


**•** You can change the global search settings for your experience. For
example, you can choose to show or hide the search bar in your
experience or change the search source that determines where the
search results come from.


Workspace edit experience settings screen

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-47-1.png)


To learn more about the workspace experience settings, see Configure UI
Builder workspace experiences.


**Portal experience settings**


You can change these settings for your portal experience:


**•** Modify or add general settings for your experience. For example, you
can change the title, the description, and the path of the workspace or
portal.


**•** Apply your organization's branding to all of the pages in your
experience or to a page within your experience.


**•** Set up the navigation and menu settings in the app shell of your portal
experience. The app shell, which is the wrapper of the portal contents,
is similar to a Google Chrome web page.


**•** Control whether the global search functionality is visible to the users of
your portal experience. For example, you can enable or disable the
global search for either your public or private pages.


Edit experience settings screen

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-48-1.png)


To learn more about the portal experience settings, see Configure UI
Builder portal experiences.

## Helpful resources for UI Builder


Some ServiceNow resources that can provide you with helpful
information.


Some ServiceNow resources that can provide you with helpful
information are:


**Component Documentation**


[Components documentation](https://developer.servicenow.com/dev.do#!/reference/next-experience/components?&query=&order_by=nameAsc&limit=120&offset=0&categories[]=uib_component&categories[]=uib_macroponent-component&categories[]=uib_facades)


[Component Design Documentation](https://horizon.servicenow.com/workspace/components)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-50-1.png)


**ServiceNow Community**


[ServiceNow Community site](https://www.servicenow.com/community/next-experience-articles/ui-builder-resources/ta-p/2332009)


[You and I Builder Bytes!](https://www.servicenow.com/community/next-experience-articles/you-and-i-builder-bytes-article-hub/ta-p/3241157)


**Development information**

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-51-1.png)


[ServiceNow Developer site](https://developer.servicenow.com/)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-52-1.png)


**ServiceNow University**


[ServiceNow University](https://nowlearning.servicenow.com/lxp/en/pages/servicenow)


**Support**


[https://support.servicenow.com/now](https://support.servicenow.com/now)


[Search the Known Error Portal for known error articles](https://support.servicenow.com/kb?id=kb_article_view&sysparm_article=KB0597477)

## UI Builder glossary


Learn about the terms and concepts used in UI Builder (UIB).


**action**


Actions in UI Builder are specifically activity on a page or within a page
component. Events and event handlers are used to add actions. For
example, add a button component to a page and then add an event
handler to apply an action for the button, such as opening a web page.


**app shell**


App shells are the static elements of a web experience (for example,
the header, footer, and menu navigation) that stays with the end user as
they navigate throughout the experience. App shells are primarily used
and supported in Workspace and Portal experiences.


**binding**


See data binding.


**client script**


Client-side JavaScript that interact with components and client state
parameters on a page. Client scripts are mapped to events as event
handlers in UI Builder.


**client state parameter**


Page variables that are defined for a page to store a piece of data (a
client state) only for that page. For example, create three client state
parameters to store the input needed to create a record and specify
when to refresh the list. Page variables can be updated using client
scripts and events to make a page dynamic.


**component (UI Builder)**


Components are used in the UI Builder to build pages. Components have
an interface that an end user can view and interact with. Components


can talk to each other through events and properties. Commonly used
components include Heading, Image, List, Form, and Button.


**component id**


Used to reference a component when adding a script or binding data
to the component. A component ID is automatically created (based on
the component label) when you add a component to a page, but the
component ID can be edited.


**component preset**


Presets apply predefined configuration values and event mappings
to components. Presets apply prebuilt configurations to component
properties and events handlers. Presets are only available for certain
components.


**component properties**


Available in the Configuration panel and used to configure a
component. Each component has unique properties. Component
properties are specified within each tab on the Configuration panel:
Config, Style, and Event. Some components have presets available. Use
the component presets to set component properties automatically.


**controller**


A type of data resource that includes data and event logic and enables
component presets. Controllers are added automatically when using a
page template. There are two types of controllers:


**•** Data controllers contain data resources and can be manually added
to a page


**•** UI controllers are added to pages when using page templates and
can't be added manually. Creating controllers isn't supported currently.


**data binding**


The process of associating data with a UI element that displays the
information.


**data resource**


A dynamic, reusable way of defining what data to fetch for a page's
components.


**entity view action mapper**


Also known as EVAM. Standardizes the format for displaying data in cards
and lists.


**event (UI Builder)**


Action a user takes (such as selecting a button) or an occurrence that
happens on a page. Most UI Builder components, pages, and data
resources have default-associated events. Use event handlers with the
events to add additional actions to pages.


**event handler**


An action performed when an event occurs.


**event mapping**


The process of identifying an event handler to run when an event occurs.


**macroponent**


A core data structure that drives UI Builder pages. Its fields contain JSON
data that builds the page.


**modal**


A user experience window that overlays another content window and
takes control of the user experience.


**now code editor**


A rich-text editor that supports CSS, HTML, JavaScript, XML, and JSON.
Use Now Code Editor to change UI configuration, data resource
configuration, styles, events, client-side scripts, and server-side scripts in
Next Experience UI Builder components.


**page**


Collection of column layouts, columns, and components. Create
or customize multiple UI Builder pages for workspace and portal
experiences.


**page collection**


Group of pages that can be reused in experiences within tabs or modals.


**popover**


A page overlay that enables users to continue using the rest of the
page. Popovers can be configured just like UI Builder pages with text,
components, images, fields, and menu items.


**repeater**


In UI Builder, a repeater is a component that acts as a basic loop that
repeats the data you provide in multiple components. Repeaters use
an array or an array of objects. Repeaters bind values to a data array
property. For example, [{"task": "A"},{"task": "B"}], repeats the content inside
it two times.


**UI Builder (UIB)**


A WYSIWYG web user interface builder. UI Builder enables developers to
build new pages or customize existing pages for Agent Workspace and
portals using Now Experience UI Framework components.


**variant**


The version of a UI Builder page with access controlled by role or
condition. Create variants of pages to target experiences for different
audiences. For example, create a home page for agents and a variant
for managers at the same URL. Alternatively, create a page variant that
users see under different conditions.

## **Learning UI Builder**


Learn how to navigate the UI Builder and explore some common use
cases to learn by example.


**•** Navigate the UI Builder application


Learn how to navigate through UI Builder.


**•** Learn UI Builder by example


Exploring common use cases can be a great way to learn how to use UI
Builder. Consider performing each of the tasks in this section in the order
presented.


**•** Learn UI Builder using other ServiceNow resources


Learn more about UI Builder using resources outside of the product.


**•** Learn about audiences


Learn how to apply the correct audiences to your UI Builder pages.


**•** Learn about security and roles


Set up the security and roles for your UI Builder instance.


**•** Learn about domain separation


Domain separation is supported for UI Builder . Domain separation
enables you to separate data, processes, and administrative tasks into
logical groupings called domains. You can control several aspects of
this separation, including which users can see and access data.

## Navigate the UI Builder application


Learn how to navigate through UI Builder.


**UI Builder home**


The UI Builder home page provides easy access to recently opened
experiences, options for creating experiences or page collections, and
help for getting started using UI Builder. You can also use the search bar
to quickly find your experiences by name.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-60-1.png)


You can access the list of experiences in the top by selecting the
**Experiences** tab in the top bar.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-61-1.png)


You can access the list of page collections in the top by selecting the
**Page collections** tab in the top bar.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-62-1.png)


You can access the list of controllers in the top by selecting the
**Controllers** tab in the top bar.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-63-1.png)


You can access the list of presets in the top by selecting the **Presets** tab in
the top bar.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-64-1.png)


Select the **What's new** link in the header to view the latest changes to UI
Builder.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-65-1.png)


**UI Builder experience view**


The UI Builder experience view is a central place to view and understand
the structure and details of an experience. Use the **Page and Variants** list
to select a page to edit.


UI Builder experience view

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-66-1.png)


**Structure of UI Builder**


UI Builder is separated into the following areas.


**•** Use the left vertical bar for access to the following in UI Builder:


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-67-1.png)


**•** Use the top bar to access pages in the experience and view Help.
Change page settings, such as availability, order, and audience.
Preview and open the URL path for the page you're editing to see
what the page looks like for users. You can also select a domain and


set application scope. View page errors and warnings by selecting the
icon next to the save button. And finally, click the **Save** button often to

save your page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-68-1.png)


**•** Use the content tree to view and edit column layouts, columns, and
components on your pages.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-69-1.png)


**•** Add column layouts and components to your page using the UI Builder
toolbox.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-70-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-71-1.png)


**•** Work in the UI Builder staging area to build and modify your pages.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-72-1.png)


**•** Go to configuration panel to modify column layouts, columns,
components, styling, and events.


**•**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-73-1.png)


Data resources: Bind data to your components using data resources to
dynamically expose your data from tables, records, or other elements
on your page. Data resources enable you to reuse your components.
See Connect data to your components for more information.


**•**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-74-1.png)


Client state: Set the parameters for the client state for your page. The
client state parameters consist of a name, a type, and an initial value.
You can see the preview of the client state parameters.


**•**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-75-1.png)


Client scripts: Scripting automates aspects of the page, like event
handling.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-76-1.png)


**•** UI Builder Learning Center


Explore the UI Builder Learning Center for articles, videos, courses, and
guided tours to help you get started and build knowledge. The Learning
Center is a one-stop shop for learning fundamental features and basic
guidelines in UI Builder.


**•** Guided tours in UI Builder


Learn about UI Builder guided tours, including how to use them to build
your knowledge and practice using UI Builder.


**•** Dark theme in UI Builder


Learn how to switch to the dark theme in UI Builder.


## **UI Builder Learning Center**


Explore the UI Builder Learning Center for articles, videos, courses, and
guided tours to help you get started and build knowledge. The Learning
Center is a one-stop shop for learning fundamental features and basic
guidelines in UI Builder.


**Open the Learning Center**


Navigate to **All > Now Experience Framework > UI Builder > Help** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-77-1.png)


The Learning Center opens in an overlay.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-77-2.png)


Available information is listed on tiles. Each tile contains a title, the
information type, and the time to complete. For example, a tile linking
to a product documentation article that takes three minutes to read.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-78-1.png)


Select a tile to open a resource. Resources are in the following locations:


**•** [Articles: https://servicenow.com/docs](https://servicenow.com/docs)


**•** Videos: created by ServiceNow and available on public, online video
platforms


**•** [Courses: https://learning.servicenow.com](https://learning.servicenow.com/)


**•** Tours: embedded in your ServiceNow instance

## **Guided tours in UI Builder**


Learn about UI Builder guided tours, including how to use them to build
your knowledge and practice using UI Builder.


**What guided tours are**


Guided tours are part of the default ServiceNow platform. There are
guided tours available to take and you can use the Guided Tours
application to create custom tours yourself in your own instances.


Tours contain interactive steps to help train and teach users. Some tours
show various features in the user interface, such as an overview of
a homepage. Other tours help complete a task, such as creating an
experience or previewing an experience page. For more information
[about what guided tours are and how to create them, see Exploring](https://www.servicenow.com/docs/csh?topicname=exploring-guided-tours&version=zurich&pubname=zurich-platform-user-interface)
[Guided Tours.](https://www.servicenow.com/docs/csh?topicname=exploring-guided-tours&version=zurich&pubname=zurich-platform-user-interface)


**How to access and use UI Builder guided tours**


Guided tours about UI Builder may launch automatically. You can also
start them manually from the **Getting started** section of the UI Builder
homepage or the UI Builder Help panel.


When a guided tour starts automatically, an introduction is displayed.
Select **Begin Tour** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-79-1.png)


To begin a tour manually from the homepage, navigate to **All > Now**
**Experience Framework > UI Builder** and select a tour in the **Getting**
**started** section. If no guided tours appear by default in the section, select
**View more** and then select a tour on the **Find relevant resources to get**
**you unstuck** pop-up.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-80-1.png)


Alternatively, select **Help** and then select a tour on the **Find relevant**
**resources to get you unstuck** pop-up.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-80-2.png)


After a tour starts automatically or manually, you're led through a series
of steps. Read the text for each step and perform the required actions or
select **Next** to continue the tour.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-81-1.png)


To stop a tour at any time, select the **X** .


Select **Yes** or **No** to stop the tour from auto-launching again. You can
also apply your decision to all tours that start on the same page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-81-2.png)


## **Dark theme in UI Builder**


Learn how to switch to the dark theme in UI Builder.


UI Builder includes a dark theme option, offering an eye-friendly
alternative to the default light theme. You can enable dark theme by


selecting the Choose theme icon ( ) in the banner.


UI Builder theme options

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-82-1.png)


The Dark theme is instantly applied to the UI Builder interface.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-83-1.png)


**Note:** The UI Builder stage uses the theme set in your Platform theme
settings. For example, the stage might remain white even when the
rest of the interface is dark. To enable UI16 pages to render with the
dark theme on the stage, select the **Dark** option in the theme menu
of your user preferences. For more information on navigating to the
[theme menu, see Open the theme menu.](https://www.servicenow.com/docs/csh?topicname=tb-open-theme-menu&version=zurich&pubname=zurich-platform-user-interface)

## Learn UI Builder by example


Exploring common use cases can be a great way to learn how to use UI
Builder. Consider performing each of the tasks in this section in the order
presented.


The following use cases are described here.


**•** Create a demo experience to explore UI Builder


An experience in UI Builder is a collection of web pages for users to
interact with an application. The experience includes routes, page
variants, and the audience and conditions required for each variant,
as well as experience settings.


**•** Create a blank page


After creating a demo experience, you can create a blank page that
you can then build on to define what the experience provides to your

users.


**•** Create a record page using a template


After you've created your demo experience, you can create a record
page from a template. A record page shows data from a table.


**•** Define an audience for your variant


An audience represents a group of users in your organization. You
can define who can access this page variant by adding one or more
predefined audiences.


**•** Define conditions for your variant


You can define conditions to determine when a page variant is shown.
The conditions are based on setting an order, and declaring the criteria
that must be met for the page variant to display.


**•** Customize forms within a form component


Customize your form components by accessing Form Builder in UI
Builder.

## **Create a demo experience to explore UI Builder**


An experience in UI Builder is a collection of web pages for users
to interact with an application. The experience includes routes, page
variants, and the audience and conditions required for each variant, as
well as experience settings.


**Before you begin**


Role required: ui_builder_admin


**About this task**


The UI Builder experience view is a central place to view and understand
the structure and details of an experience. Use the experience view to
see the structure and hierarchy of your experience. You can access UI
Builder experience view by selecting an existing experience from the UI
Builder home screen or by creating a demo experience, as described
here.


**Note:** UI Builder is not yet capable of building or configuring
ServiceNow base system service portals, such as the Employee
[Center. For service portals, continue to use the Service Portal](https://www.servicenow.com/docs/csh?topicname=t_ConfigureAPage&version=zurich&pubname=zurich-platform-user-interface)
[Designer.](https://www.servicenow.com/docs/csh?topicname=t_ConfigureAPage&version=zurich&pubname=zurich-platform-user-interface)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


UI Builder Home page

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-86-1.png)


2. From the UI Builder Home page, select **Create** .


3. Select **Experience**
Create an experience dialog box

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-87-1.png)


4. Enter a **Name** ; for example, **Demo Experience** .


5. Select an **App shell UI** ; for example, **Workspace App Shell** .


6. Select **Create** .


7. Select **Open experience** to view the main page for your experience.


Main page for your new experience

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-88-1.png)


**Note:** In addition to the name of your new experience, the
screen includes the URL, application scope, admin panel, and
the roles of users who can view the experience. Any pages or
variants you create for the experience appear in the **Pages and**
**variants** section.


**What to do next**


Select the **Next topic** link to learn how to create a blank page for this
experience.


Related tasks


**•** Create a blank page


**•** Create a record page using a template


**•** Define an audience for your variant


**•** Define conditions for your variant


**•** Customize forms within a form component

## **Create a blank page**


After creating a demo experience, you can create a blank page that
you can then build on to define what the experience provides to your

users.


This video shows you how to perform the following procedure.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. If you aren't already viewing the experience you created in the
previous procedure, navigate to **All > Now Experience Framework**

**> UI Builder**, and select the experience you created.


Main page for your new experience

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-90-1.png)


2. From the main page for your experience, either select **Create new**
**page** or select the plus ( **+** ) sign next to **Pages and variants** .


3. On the **First, select a template** screen, select **Create from scratch**
**instead** .


There are templates you can use, but we are going to create a page
from scratch.


Page details

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-91-1.png)


4. In the **Name** field, type **My test page**, and select **Continue** .


**Note:** The **URL path** shows the URL that users can navigate to
access the page.


5. Select **Looks good** on the next screen.


6. On the **Tell us about your variant** screen, do not make any changes.


7. Select **Continue** .


8. Select the **Build responsive** option (default) for greater control of how
the page appears at different screen widths.


9. Select **Create** .
The visual editor opens. Here, you can begin editing your new page.


UI Builder visual editor

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-92-1.png)


**What to do next**


Select the **Next topic** link to learn how to create a button that opens a
modal.


Related tasks


**•** Create a demo experience to explore UI Builder


**•** Create a record page using a template


**•** Define an audience for your variant


**•** Define conditions for your variant


**•** Customize forms within a form component

## **Create a record page using a template**


After you've created your demo experience, you can create a record
page from a template. A record page shows data from a table.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Open the main page for your demo experience.
Demo Experience

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-93-1.png)


2. From the main page for your experience, select the plus ( **+** ) sign next
to **Pages and variants** .


Create a new page or variant

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-94-1.png)


3. Select **Create a new page** to create a page that resides at a
different URL.


4. On the **First, select a template** screen, locate the **Standard record**
template and select **Use template** .


**Note:** Optionally, you could select **Learn more** to read about
the template before selecting it.


Page details

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-94-2.png)


5. In the **Name** field of the Page details screen, type `Task record`
`page`, and select **Continue** .


6. Select **Looks good** on the next screen.


7. On the **Tell us about your variant** screen, enter a condition to
determine when the page is visible.


a. In the **Parameter** field, select **table** .


b. In the **Operator** field, select **is** .


c. In the **Value** field, enter `task` .

Condition fields

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-95-1.png)


This page is visible to users accessing a record from the Task table.


8. Select **Create** .
The visual editor opens. Here, you can begin editing your new page.


New page created from Standard Record template

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-96-1.png)


**Note:** The new page includes LOTS of layout, preconfigured
components, data, and modals. Additionally, it includes test
values you can modify for your own particular use cases. Using
templates can be a significant time-saver when creating new

pages.


9. You can select the area above the Page content pane to view
information about test values included in the template.


Edit test values included in the template

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-97-1.png)


**What to do next**


Select the **Next topic** link to learn how to define audiences who can view
your pages in UI Builder.


**•** Create a button that opens a modal


After you've created your demo experience and added a blank page,
you can edit the page variant as needed. For the sake of this demo,
you can create a button and a modal, and configure the button to
open the modal.


Related tasks


**•** Create a demo experience to explore UI Builder


**•** Create a blank page


**•** Define an audience for your variant


**•** Define conditions for your variant


**•** Customize forms within a form component


After you've created your demo experience and added a blank page,
you can edit the page variant as needed. For the sake of this demo, you
can create a button and a modal, and configure the button to open the
modal.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Open the UI Builder page for your demo experience.


UI Builder visual editor

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-99-1.png)


2. Click the **+ Add content** button on the stage to open the toolbox.


3. Select a **Single column** layout.


4. Next, click the **+** icon in the column to open the toolbox.


5. Select the **Button** component to add it to the stage.


Add a button

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-100-1.png)


**Note:** When you have selected the component, the Page
configuration pane includes some presets you can use to
automatically configure components on compatible pages. For
the sake of this exercise, however, you will be configuring the
component manually. For more information on presets, see
Customize UI Builder pages using components.


6. Select **Add** .


7. In the Page configuration pane, select **Configure the component**
**manually** .


8. In the Page content pane, select **Button 1** and, in the Configuration
pane, change the button label to **Open modal** .


9. Select **Save** .


10. In the Page content pane, click the plus icon next to **Modals** and
select an **Alert** modal.

Add an Alert modal

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-101-1.png)


11. Select **Save** .


12. In the Page contents pane, select **Button 1** and, in the Configuration
pane, select the **Events** tab.


13. Select **+ Add event handler** and, under **Inherited event handlers**,
select **Open or close modal dialog** .


Show/hide modal configuration

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-102-1.png)


14. Activate the **Open modal dialog** and, select **Alert 1** in the **Modal**
field, and select **Add** .


15. Select **Save** .


16. Select **Preview** .


17. When the preview opens, select **Open modal** .
The modal you defined opens.


Open modal with button

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-103-1.png)


18. Select **Got it** in the modal, and then select the browser back button
to return to the experience main screen.


**What to do next**


Select the **Next topic** link to learn how to create a page using a
template.

## **Define an audience for your variant**


An audience represents a group of users in your organization. You
can define who can access this page variant by adding one or more
predefined audiences.


**Before you begin**


Role required: ui_builder_admin


**About this task**


In the previous procedure, you created a page variant that can be
viewed by anyone accessing a record from the Task table. For this
procedure, you will duplicate the variant and configure it so that it is
accessible only to audiences with the Admin role.


**Procedure**


1. Open the main page for your demo experience.


2. Select the experience you created, and select **Default** .
Demo Experience

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-104-1.png)


3. Select the **Open menu** icon.
Open menu

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-104-2.png)


4. Select **Duplicate variant** .


5. On the **Tell us about your variant** screen, enter **Admin only** in the
**Name** field.


6. Select **+ Add** next to **Audiences**, and select the **Admin** audience.


Select the Admin audience

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-105-1.png)


7. Select **Create** .
The variant is duplicated and only users with the Admin role can view
this page.


**What to do next**


Select the **Next topic** link to learn how to apply conditions to the variant
so that the variant is visible only when the defined conditions are met.


Related tasks


**•** Create a demo experience to explore UI Builder


**•** Create a blank page


**•** Create a record page using a template


**•** Define conditions for your variant


**•** Customize forms within a form component


## **Define conditions for your variant**


You can define conditions to determine when a page variant is shown.
The conditions are based on setting an order, and declaring the criteria
that must be met for the page variant to display.


This video shows you how to perform the following procedure.


**Before you begin**


Role required: ui_builder_admin


**About this task**


If you have multiple page variants that all have the same conditions, the
variants go by the order setting.


**Procedure**


1. Open the main page for your demo experience.


2. Select the experience you created, and select **Default** .
Demo Experience

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-107-1.png)


3. On the Default variant under the **All users record page**, select the


**Menu** icon ( ), and select **Duplicate variant** .


4. On the **Tell us about your variant** screen, enter **Incident record page**
in the **Name** field.


5. Since the intent of this task is to restrict this page to users who are
opening a record in the Incident table, enter the following under
Conditions:


a. In the **Parameter** field, select **table** .


b. In the **Operator** field, select **is** .


c. In the **Value** field, replace the text with `incident` .


When you created this page earlier in the series, you set this
condition to the Task table. Now, you are configuring the page
to display only to users accessing a record from the Incident
table.


Condition fields

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-108-1.png)


6. Select **Create** .


Incident record page

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-109-1.png)


**Note:** You can view the structure of your pages and variants
in this experience. The **Conditions** column shows a **View** link for
each page. You can select **View** to see the condition for that
variant (that is, table=incident). The **Audiences** column for the
Admin only variant shows a 1. You can select the **1** to view the
role required to view that variant.


Related tasks


**•** Create a demo experience to explore UI Builder


**•** Create a blank page


**•** Create a record page using a template


**•** Define an audience for your variant


**•** Customize forms within a form component

## **Customize forms within a form component**


Customize your form components by accessing Form Builder in UI Builder.


**Before you begin**


Role required: admin


**About this task**


You can edit form components without leaving UI Builder. Access Form
Builder from within a form component on the UI Builder stage. After you
save the form, your edits remain, and anyone who views the form sees
the modified version. Changes made in Form Builder are reflected on the
stage.


**Procedure**


1. Add a form component to your page.


a. In the content tree, select **+ Add content** .


b. Select **Form** .


2. On the stage, move your cursor to the form component to display
the **Edit Form** button.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-111-1.png)


3. Select the **Edit Form** button.
Form Builder opens in a full-screen modal.


4. (Optional) Move your cursor to individual fields to display additional
options.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-111-2.png)


5. (Optional) Insert fields by moving your cursor to the **+** button, which
displays the **+ Add** button, then selecting **+ Add** .
You can also drag additional fields onto the form from the **Fields**
column.


For example, you can add the **Due date** field below the
**Configuration item** field, then select **Save** and **Preview** to save and
preview the form.


6. (Optional) Move a field by dragging the edge of a field to another
place in the form and then selecting **Save** .
For example, select the **State** field and place it below the **Duplicate**
**of** field, then select **Save** .


7. (Optional) Delete a field by selecting the **X** button on the field.


8. Select **Save** .


9. Close Form Builder to see your edits appear on the stage.


**What to do next**


You can enhance the functionality of a custom form by configuring
[additional features. For more information, see Forms in Table Builder.](https://www.servicenow.com/docs/bundle/zurich-application-development/page/administer/ui-builder/task/../../form-builder/concept/form-view-configuration.html)


Related tasks


**•** Create a demo experience to explore UI Builder


**•** Create a blank page


**•** Create a record page using a template


**•** Define an audience for your variant


**•** Define conditions for your variant

## Learn UI Builder using other ServiceNow resources


Learn more about UI Builder using resources outside of the product.


|Learn more about UI Builder|Additional ServiceNow resources|
|---|---|
|UI Builder is a web user<br>interface builder. Use UI<br>Builder to build pages for<br>CSM Configurable Workspace,<br>App Engine Studio generated<br>workspaces and portals, or custom<br>web experiences using Next<br>Experience Components and<br>custom web components.|ServiceNow Dev<br>Program YouTube channel|
|UI Builder is a web user<br>interface builder. Use UI<br>Builder to build pages for<br>CSM Configurable Workspace,<br>App Engine Studio generated<br>workspaces and portals, or custom<br>web experiences using Next<br>Experience Components and<br>custom web components.|Community YouTube<br>channel|
|UI Builder is a web user<br>interface builder. Use UI<br>Builder to build pages for<br>CSM Configurable Workspace,<br>App Engine Studio generated<br>workspaces and portals, or custom<br>web experiences using Next<br>Experience Components and<br>custom web components.|ServiceNow Community<br>site|
|UI Builder is a web user<br>interface builder. Use UI<br>Builder to build pages for<br>CSM Configurable Workspace,<br>App Engine Studio generated<br>workspaces and portals, or custom<br>web experiences using Next<br>Experience Components and<br>custom web components.|Developer Advocate<br>blog|
|UI Builder is a web user<br>interface builder. Use UI<br>Builder to build pages for<br>CSM Configurable Workspace,<br>App Engine Studio generated<br>workspaces and portals, or custom<br>web experiences using Next<br>Experience Components and<br>custom web components.|ServiceNow Developer<br>site|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-114-1.png)


## Learn about audiences

Learn how to apply the correct audiences to your UI Builder pages.


**Audiences**


Understanding your audiences in UI Builder is an important part of
creating pages. The audience defines who can see your pages. You
create pages for targeted experiences tailored to audiences and roles
such as agents and managers. For example, you may want to create a
page for agents to solve issues for your employees. You want to ensure
that only people who have the agent role can see the page.


Audiences are generally made of allow/deny lists based on role and
domain. They can also target the following:


**•** Role


**•** Group


**•** User


**•** Company


**•** Department


**•** Location


**•** Script


You can set audiences to fit a specific role based on one or more criteria.
For example, you could create an audience for an ITSM user in Europe
who is not a manager.


The glide.ux.user_criteria_enabled property needs to be set to **true** to
configure access for users based on role, department, group, location, or
company. See Enable the user criteria property, for more information.


Set an audience in UI Builder when you create your page or page
variant. You can also set the priority of the audience record. The lower
the number the higher the priority. Ensure the **Active** check box is
selected to make this page active.
Add audiences modal

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-115-1.png)


If you do not see an audience that you need, you can click **Open**
**audiences in platform** to define an audience in the ServiceNow AI
Platform®.


**•** Choosing an audience from the list in the **Audience** field.


Audience list

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-116-1.png)


**•** Selecting **Open audiences in platform** to edit or create an audience
record in the ServiceNow AI Platform®.


**•** If you have multiple audiences, define the **Order** for each audience
record. The order defines the importance of each audience record.
For example, a CSM Manager could have a higher priority than a CSM
Consumer Agent. To give higher priority to an audience, enter a lower
number.


**•** Ensuring the **Active** check box is selected to make this page active.

## Learn about security and roles


Set up the security and roles for your UI Builder instance.


Security and roles in UI Builder are controlled through your application
scope, domain separation, and protection policy settings.


**Roles**


Roles control access to features and capabilities in UI Builder. The admin
role provides access to all features and capabilities. After access has
been granted to a role, all the groups or users assigned to the role
are granted the access. Roles can contain other roles, and any access
granted to a role is granted to any role that contains it. For more
[information, see Managing roles.](https://www.servicenow.com/docs/csh?topicname=ua-creating-roles&version=zurich&pubname=zurich-platform-administration)


**Application scope**


Application scoping protects applications by identifying and restricting
access to application files and data. Administrators can specify what
parts of an application are accessible to other applications, which helps
to protect data and application files. In UI Builder, System administrators
and developers set application scope when creating a page. Note,
you cannot change the application scope after creating the page, so
choose your scope carefully.


Changing the scope in UI Builder also changes the scope in the
ServiceNow AI Platform®, and vice versa.


When creating a page, it’s important for admins and developers to be
aware of the scope they are in for the workspace or portal experience.
Choose the correct application scope for your experience. The scope
picker is to the right of the URL field. The scope defaults to the scope that
the user is currently in within the ServiceNow AI Platform®.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-117-1.png)


If you change to a different scope while in a page, you’re notified that
you are in a different application scope from the one the page was
[created in. For more information, see Application scope.](https://www.servicenow.com/docs/bundle/zurich-application-development/page/administer/ui-builder/task/../../../build/applications/concept/c_ApplicationScope.html)


**Delegated developers for UI Builder**


If you have the application-specific admin role or the system-level admin
role, you can delegate application development in ServiceNow® Studio
to designated developers at the UI Builder application level.


**Protection policy**


A protection policy prevents anyone from modifying and/or copying
an application file or its related record. A protection policy is typically
used when the author of an application is different than the company
that uses the application. UI Builder notifies you if you try to modify a
[protected record. For more information, see Application file protection](https://www.servicenow.com/docs/bundle/zurich-application-development/page/administer/ui-builder/task/../../../build/applications/concept/c_ProtectingApplicationFiles.html)
[policy.](https://www.servicenow.com/docs/bundle/zurich-application-development/page/administer/ui-builder/task/../../../build/applications/concept/c_ProtectingApplicationFiles.html)

## Learn about domain separation


Domain separation is supported for UI Builder . Domain separation
enables you to separate data, processes, and administrative tasks into
logical groupings called domains. You can control several aspects of this
separation, including which users can see and access data.


**Support level: Standard**


**•** Includes all aspects of **Basic** level support.


**•** Application properties are domain-aware as needed.


**•** Business logic: The service provider (SP) creates or modifies processes
per customer. The use cases reflect proper use of the application by
multiple SP customers in a single instance.


**•** The instance owner must configure the minimum viable product (MVP)
business logic and data parameters per tenant as expected for the
specific application.


Sample use case: An admin must be able to make comments required
when a record closes for one tenant, but not for another.


[For more information on support levels, see Application support for](https://www.servicenow.com/docs/csh?topicname=domain-separated-apps&version=zurich&pubname=zurich-platform-security)
[domain separation.](https://www.servicenow.com/docs/csh?topicname=domain-separated-apps&version=zurich&pubname=zurich-platform-security)


**Overview of Domain Separation in UI Builder**


UI Builder is a web user interface builder. UI Builder enables developers to
build new pages or customize existing pages for web-based workspace
experiences using Next Experience Components and custom web
components. In addition, UI Builder supports Domain Separation, which
is the ServiceNow® instance-wide multi-tenant architecture.


Enable developers or dashboard builders in domain-separated
environments to safely create UI application screens or dashboards while
in the same browser window. Domain Separation in UI Builder works
similarly to application scope to help administrators safely create or edit
in a multi-tenant environment.


It’s important to understand a key principle to maintaining a stable,
healthy, and scalable ServiceNow® instance, where Domain Separation
is installed.The primary principle is standardization. Standardization means
a common configuration that most the instance operates by. When
an instance has hundreds or thousands of domains, managing them
successfully requires rigorous governance. Domain-specific configurations
should be used only if they are deemed necessary by the instance
owners. Generally, most instances should follow the common instance
configuration. Doing so provides a more uniform experience across the
instance. It also lets instance owners minimize code sprawl that slows
the adoption of new ServiceNow® features included as part of release
upgrades.


**How domain separation works in UI Builder**


Domain separation in UI Builder works similarly to application scope to
help administrators safely create or edit in a multi-tenant environment.


UI Builder is compromised of a framework of interlocked components that
you use to create web-based workspaces, dashboards, or portals. While
the application supports domain separation, it does not mean every
component or table is domain separated, which is important for instance
owners to understand.


If the current domain does not match the domain of the variant or
dashboard, the record is read-only. If a user has access to the domain,
they can choose to switch their domain to the domain of the record.


Alternatively, users can edit the record. Editing the record temporarily
forces the user session into that record’s domain. They can then make
edits without fear of accidentally creating an override.


The following diagram shows what is (in green) and is not (in blue)
domain separated in UI Builder.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-120-1.png)


Not shown in the diagram are viewports, declarative actions, and screen
applicabilities, which are domain supported as process.


Data and Process/UI separation are important when considering domain
separation architecture. UI Builder fully supports data and process/UI
separation, and any data (records) displayed in the web-based
workspace, dashboard, or portal experiences.


For example, a change request that belongs to the domain of Acme
only shows for users who have access to the domain of Acme in an
experience built using UI Builder. Conversely, if an application does not
support data separation, its records won't be domain separated by the
workspace or portal experience.


Process/UI separation tables that form the underpinning framework in UI
Builder are process separated, and a sys_override column exists on those
tables. For example, if a page is created in Global, any changes to the
logic created and saved in a sub domain results in an override.


For items that are not domain separated, any change to the logic
globally affects any page or dashboard that references its content.
Understanding domain separation is critical when interacting with these
elements.


**Domain Selection menu, messaging, and managing overrides**


When designing a workspace, dashboard, or portal experience using
the UI Builder (including Dashboard Builder), a system administrator or
ui_builder_admin has access to a **Domain Selection** menu in UI Builder.
A system administrator or ui_builder_admin should switch to the proper
domain prior to creating, editing, or overriding a variant or dashboard

page.


By default, the ui_builder_admin role does not have access to the
**Domain Selection** menu. The **Domain Selection** menu must be coupled
with a role that grants access, such as ITIL, or it can be added via system
[property. For more information, see Enable domain selection menus in](https://www.servicenow.com/docs/csh?topicname=t_EnableDomainReferencePickerProperty&version=zurich&pubname=zurich-platform-security)
[Core UI.](https://www.servicenow.com/docs/csh?topicname=t_EnableDomainReferencePickerProperty&version=zurich&pubname=zurich-platform-security)


In addition, the **Domain Selection** menu also shows **Expand/Collapse**
**Domain Scope**, that is displayed while the system administrator or
ui_builder_admin is in Global. Select **Expand** to show any variant or
dashboard that has been overridden, or exists as a standalone in a sub
domain. Select **Collapse** to only show variants or dashboards created in
Global.


Lastly, domain hierarchy is available from the **Domain Selection** menu.
For deep-domain hierarchies, the user may have to collapse the
branches of the domain hierarchy to physically select the domain. In
these environments, perform a search to find the domain.


UI Builder has governance controls for editing and overriding variants
or dashboards, similar to the way application scope is handled. Both
application scope and domain scope are handled concurrently in UI
Builder.


For example, if a variant was created in Global, but the current domain
of the system administrator is set to Acme, then that variant is read-only.


As long as that screen is not in a private scope that prevents editing,
the system administrator or ui_builder_admin have two options. They
can temporarily transact into the global domain if they have access to
Global. Or, they can create an override.


You can edit the domain separation to make quick changes to the
variant or dashboard and its content. When you edit the domain, you
temporarily transact into the same domain scope as the variant or
dashboard. Going into the same scope prevents accidental overrides
when modifying certain settings (such as Name, Order, Event Mappings,
Page Definition configurations) tied to the variant. While in edit mode,
not all settings are available in page management. For full capabilities,
switch into the correct domain prior to editing the record.


Create Override allows a system administrator or ui_builder_admin to
create an override of an existing variant or dashboard. Create an
override of a variant or dashboard to perform an extensive copy of
the page definition content, minus screen conditions and audiences in
the user’s currently selected domain. The sys_override column is then
updated appropriately.


Viewports, which are variants in and of themselves, are domain
separated, and are typically nested inside page definition content. Some
viewports may not copy over. For example, a viewport (displayed as
a tab set) that was created as an override in a domain of a Global
viewport would not be carried in the page definition content during the
override creation process.


As screen conditions and audiences may be specific to a domain, this
content is not carried over during the override creation process. A screen
prompts the system administrator or ui_builder_admin to create screen
conditions and audiences.


A user cannot create an override of a variant or dashboard in Global if

the item exists in a sub domain, or if an override exists for that variant or
dashboard in the same sub domain.


After the override and the conditions and audiences are set, the content
and configurations can be configured as needed. As standard to
domain separation, the override is no longer affected by any changes
done to the original variant or dashboard. The workspace, dashboard,
or portal experience displays these overridden configurations if the user’s
current domain session is within the affected domain or sub domains


where this override was created. Audiences further determine what a
user may or may not see.


In addition, a user can access the domain hierarchy to view existing
overrides from higher domains. For example, Global <- Top <- Acme <Current domain. If no overrides exist, the default variant or dashboard
are displayed. The exception is if the default variant or dashboard is in a
child domain or a peer domain.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-123-1.png)


If you select **Expand Domain Scope** while in Global, all variants and
overrides in sub domains are shown as previously mentioned.


System administrators and ui_builder_admin can see what has been
created in the ServiceNow® platform.


**Viewports and domain separation**


Viewports are variants that can be nested in page definition content.
They can be created as a common configuration in Global, or can be
overridden per sub domain.


**Declarative actions and domain separation**


Declarative Actions can be overridden per domain as well. A system
administrator or ui_builder_admin should select the appropriate domain
prior to creating a domain specific declarative action override.


Related topics


**•** [Domain separation for service providers](https://www.servicenow.com/docs/csh?topicname=domain-sep-landing-page&version=zurich&pubname=zurich-platform-security)

## **Working in UI Builder**


Get a full understanding of everything that you can do when creating a
page for your workspace or custom portal experience in UI Builder.


**Using UI Builder resources**


The following information helps you along your UI Builder journey:


**•** Configure how users interact with your applications in UI Builder


Learn what an experience is in UI Builder. Understand what an
experience contains.


**•** Manage UI Builder pages and page variants


Learn what a page is in UI Builder. Understand the building blocks of a
UI Builder page, such as column layouts and components.


**•** Organize components in UI Builder pages


Column layouts organize components on a UI Builder page. Learn how
column layouts are used in UI Builder.


**•** Customize UI Builder pages using components


Learn what a component is in UI Builder. Also, see how components
work within UI Builder.


**•** Manage actions in UI Builder pages


Learn how to work with events so that you can add actions to
components, pages, data resources, and declarative actions in UI
Builder.


**•** Manage the visual style of UI Builder experiences


Themes enable you to change the visual style of your UI Builder
experiences so that they express the look and feel of your brand


**•** Collaborate with other UI Builder developers


UI Builder provides real-time collaboration tools and user presence
indicators for more efficient and intuitive UI development.


**•** Find and fix issues in UI Builder


UI Builder can help identify common configuration issues and guidance
on how to fix them.


**•** Getting help with the Now Assist panel in UI Builder


Get Now Assist's AI-driven guidance while working in UI Builder.

## Configure how users interact with your applications in UI Builder


Learn what an experience is in UI Builder. Understand what an
experience contains.


**What is a UI Builder experience**


An experience in UI Builder is a collection of web pages for users to
interact with an application.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-126-1.png)


Many websites use the same basic structure on every page. For example,
every page contains the same header, the same footer, and the same
menus. These common page elements are called a shell. Experiences
can have a shell, or wrapper, for each page in the experience. A shell
gives an experience a consistent look and feel as users navigate from
page to page. Shells are recommended but not required. For more
information, see Define UI experiences using app shells.


**Ways to create an experience**


You can Create an experience for UI Builder from scratch or use UI
generation to assist you in building an experience.


**Experience view in UI Builder**


The UI Builder experience view is a central place to view and understand
the structure and details of an experience. This includes routes, page
variants, and the audience and conditions required for each variant, and
experience settings. Use the experience view to see the structure and
hierarchy of your experience.


**•** View the experience URL, application scope, app shell, and roles for
the experience.


**•** Edit experience settings.


**•** Quickly view and compare variants.


**•** Create pages and page variants.


**•** View a list of page collections.


**•** Edit page and page variant settings.


**•** Duplicate page variants.


UI Builder experience view

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-128-1.png)


**•** Create an experience for UI Builder


Learn how to create a workspace or portal experience for UI Builder in
the ServiceNow platform.


**•** Configure UI Builder workspace experiences


You can change the UI Builder workspace experience settings to fit
your company goals.


**•** Configure UI Builder portal experiences


You can change your UI Builder custom portal experience settings to
affect how your users interact with your portal experience.


**•** Define UI experiences using app shells


Understand what app shells are, what app shells are available for UI
Builder, and why you would pick one over another.

## **Create an experience for UI Builder**


Learn how to create a workspace or portal experience for UI Builder in
the ServiceNow platform.


**Before you begin**


Role required: ui_builder_admin


**About this task**


This task shows you a basic example of how to create a workspace
or portal experience for UI Builder. This example creates an experience
called Demo Experience to demonstrate the process.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Select **Create** from the UI Builder home page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-130-1.png)

3. Select **Experience** .


4. In the form, fill in the fields.


Create an experience dialog box

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-131-1.png)


**Create an experience form**


|Field|Description|
|---|---|
|Name|Add a name to track<br>your experience internally. The<br>experience name is visible to users<br>from the browser tab. For this<br>example, it is`MyApp`.|
|App Shell UI|You must choose an app shell<br>for the experience to work. For<br>example, you could choose a<br>workspace or portal app shell. The<br>app shell is the wrapper of the<br>page contents, which is similar to<br>the functionality of a web page.<br>The app shell can show things like<br>the logo of your company, user<br>preferences, the search icon. For<br>more information, seeDefine UI<br>experiences using app shells.|


|Field|Description|
|---|---|
|URL path|Add a path for your experience.<br>The path appends to the end<br>of the URL parameter of your<br>experience. For example, if you<br>used`MyApp` as the title for<br>your experience, you could type<br>`my/app` for the path.|
|Landing path|The landing path is the prefix<br>that people use to reach<br>your experience homepage. To<br>designate a page as the<br>homepage, you must create a<br>page that has a matching path.|
|Roles|Only users with these assigned<br>roles can access the experience.<br>If you leave this field empty, the<br>experience is open to all logged-in<br>users by default.|


5. Select **Create** to create your experience.


6. Select **Open experience** to view the main page for your experience.


Main page for your new experience

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-133-1.png)


**Note:** In addition to the name of your new experience, the
screen includes the URL, application scope, admin panel, and
the roles of users who can view the experience. Any pages or
variants you create for the experience appear in the **Pages and**
**variants** section.


**What to do next**


Now that you have created an experience you can add and customize
pages. For more information, see Manage UI Builder pages and page
variants.

## **Configure UI Builder workspace experiences**


You can change the UI Builder workspace experience settings to fit your
company goals.


By changing the experience settings, you can affect how your users
interact with your workspace experience, how your workspace looks,
and how users navigate to and around your workspace.


Before you can edit the experience settings, you must be in the
correct application scope. If you're in a different scope, the experience
settings are read-only. To change your application scope, go to the


main header, select the application picker ( ), and then select
the application scope that you want. For more information about the
application scope, see Learn about security and roles.


Learn how you can change these workspace experience settings:


**•** Change or add the workspace general settings for your workspace
experience. For example, you can change the title, the description,
and the path of the workspace.


**•** View the brand and theme setting in your workspace experience to
see the theme currently assigned to your experience. The theme sets
the look and feel of the experience.


**•** Change the workspace side navigation settings to add pages to the
side navigation in your workspace experience.


**•** Modify the workspace utility settings to turn on or turn off notifications
for your workspace experience. Also, you can change the global
search settings for your workspace experience. For example, you can
choose to show or hide the search bar in your workspace experience
or change the search source that determines where the search results
come from.


Experience settings for workspace

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-135-1.png)


**•** Change the general settings in your workspace experience


Change the general settings for your workspace experience in UI
Builder to fit the needs of your organization. For example, you can
modify the title, description, and path for your workspace experience.


**•** View the brand and theme setting in your workspace experience


View the theme setting for your workspace experience in UI Builder. The
theme sets the visual style of the experience and provides a consistent
look and feel across all pages.


**•** Change the navigation and menu settings in your UI Builder workspace
experience


Select pages for side navigation in your UI Builder workspace
experience. From any page in the workspace experience, users can
navigate to the pages you selected.


**•** Set up notifications in workspace utility settings


Set up the advanced notification and search settings in your
workspace experience so that you can control how your users see
notifications and search options.


**•** Display global search in a workspace experience


Show or hide the search functionality in your workspace.


Change the general settings for your workspace experience in UI Builder
to fit the needs of your organization. For example, you can modify the
title, description, and path for your workspace experience.


This video show you how to perform the following procedure.


**Before you begin**


You must be in the correct application scope to edit the experience
settings. If you're in a different scope, the experience settings are readonly. To change your application scope, go to the main header, select


the application picker ( ), and then select the application
scope that you want. For more information about the application scope,
[see Application scope.](https://www.servicenow.com/docs/bundle/zurich-application-development/page/administer/ui-builder/task/../../../build/applications/concept/c_ApplicationScope.html)


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Select **View experience settings** in the upper right.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-137-1.png)


4. Change the title, description, and path of your workspace
experience.


**•** The title lets everyone know what the workspace is called. Take
care when choosing a name for your workspace.


**•** The description lets your users know the details of the workspace.


**•** The path must be unique. The path can include digits (0-9), letters
(A-Z, a-z), and a few special characters ( `"-"`, `"."`, `"_"`, or `"~"` )
with the words separated by a forward slash or hyphen.
UI Builder experience settings

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-138-1.png)


5. (Optional) Select **Advanced settings** to edit the workspace record on
the ServiceNow AI Platform.


a. Update the record in the platform when you’re finished.


When you go back to your workspace experience settings in
UI Builder, you see the changes that you made to the general
settings.


6. Click **Save** .


View the theme setting for your workspace experience in UI Builder. The
theme sets the visual style of the experience and provides a consistent
look and feel across all pages.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select **View experience settings** in the upper-right.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-139-1.png)


4. Scroll to the **Branding and theming** section and note what is listed in
**Themes** .
By default, the Polaris theme is applied to UI Builder experiences.


**What to do next**


If you want to customize the theme, there are two options:


**• Theme Builder** enables you to create, edit, manage, and apply
Next Experience themes using a friendly visual interface. For more
[information, see Configuring Next Experience with Theme Builder.](https://www.servicenow.com/docs/csh?topicname=configuring-next-experience-with-theme-builder&version=zurich&pubname=zurich-platform-user-interface)


**•** If you are an admin user comfortable working in style records and JSON
code, you can create a custom theme to override the default Polaris
style. This option gives you the most control over typefaces, colors,
and images (including the banner and logo) in a theme. For more
[information, see Configuring Next Experience themes and preferences.](https://www.servicenow.com/docs/csh?topicname=config-next-experience-themes-prefs&version=zurich&pubname=zurich-platform-user-interface)


Select pages for side navigation in your UI Builder workspace experience.
From any page in the workspace experience, users can navigate to the
pages you selected.


**Before you begin**


This task has the following prerequisites:


**•** You have an existing workspace experience on UI Builder. For more
information, see Configure how users interact with your applications in
UI Builder.


**•** This workspace experience was created with the Workspace App Shell.


**•** This workspace experience includes at least two pages.


**•** You want users to be able to navigate from a page to other pages that
you specify.


Role required: ui_builder_admin


**About this task**


You can add up to seven pages to your side navigation.


You must be in the correct application scope to edit the experience
settings. If you are in a different scope, the experience settings are
read-only. To change your application scope, go to the main header,


select the application picker ( ), and then select the application
scope that you want. For more information about the application scope,
see Learn about security and roles.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open your workspace experience in the UI Builder.


3. Select **View experience settings** in the upper-right.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-141-1.png)


4. Scroll down to **Side navigation** .


5. Select **+ Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-142-1.png)


6. Fill in the following fields:


**Field** **Description**


|URL path (required)|Select the page that you want<br>to navigate to.<br>Tip: The landing page is<br>usually the first page that<br>you want a link to.|
|---|---|
|Icon|Select an icon for the link.<br>Default: No icon|
|Label (required)|Enter a name for the page,<br>which appears in a tooltip for the<br>link.|
|Group|Place the link in the top or<br>the bottom group of the side<br>navigation panel.<br>Default: Top|


7. Add more pages as needed.


8. Select **Save** .


9. Select the experience name (for example, Demo Experience) in the
UI Builder header.


10. Select the **URL path** link to open the experience in a new tab and
check that the side navigation is displayed on the left side.


**Tip:** If the side navigation doesn’t work as expected, consider
reviewing the UX Page Property [sys_ux_page_property] record
underlying the side navigation. Reopen the Side Navigation
experience settings, as described in Steps 3-4. Select **Advanced**
**side navigation settings** to open the record. Verify that the fields
have the correct values, such as Type= `json` .


Set up the advanced notification and search settings in your workspace
experience so that you can control how your users see notifications and
search options.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Set up the advanced notification and search settings in your workspace
experience. You can turn notifications on or off to control how people
see notifications in your workspace experience.


Workplace experience settings

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-144-1.png)


You can also control whether the search functionality is visible to the
users of your workspace experience. If you choose to display a search
option, you can define what search results are returned by choosing a
source for the search.


Before you can edit the experience settings, you must be in the
correct application scope. If you're in a different scope, the experience
settings are read-only. To change your application scope, go to the


main header, select the application picker ( ), and then select
the application scope that you want. For more information about the
application scope, see Learn about security and roles.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page in your workspace experience.


4. Select **View experience settings** in the upper-right.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-145-1.png)


5. Scroll down to **Notifications** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-145-2.png)


6. Select the **Turn on notifications** option.


7. Click **Save** .


8. (Optional) Click **Advanced settings** to go to the ServiceNow AI
Platform® and edit the JSON values of the record.


**Note:** If you have the Record component on a page, you
can have a record open in the workspace experience when a
[notification is selected. Follow the instructions in Record UIB Setup](https://developer.servicenow.com/dev.do#!/reference/next-experience/washingtondc/now-components/record/uib-setup)
on the ServiceNow developer site and define a featureRoutes
page property.


Show or hide the search functionality in your workspace.


**Before you begin**


Role required: ui_builder_admin


**About this task**


You can control whether the search functionality is visible to the users of
your workspace experience. If you choose to display a search option,
you can define what search results are returned by choosing a source for
the search.
Workplace experience settings

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-146-1.png)


Before you can edit the experience settings, you must be in the
correct application scope. If you're in a different scope, the experience
settings are read-only. To change your application scope, go to the


main header, select the application picker ( ), and then select
the application scope that you want. For more information about the
application scope, see Learn about security and roles.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .


For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page in your workspace experience.


4. Select **View experience settings** in the upper-right.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-147-1.png)


5. Scroll down to **Global search** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-147-2.png)


6. Select the **Show global search** option.


7. Click **Save** .


8. (Optional) Click **Advanced settings** to go to the ServiceNow AI
Platform® and edit the JSON values of the record.


## **Configure UI Builder portal experiences**


You can change your UI Builder custom portal experience settings to
affect how your users interact with your portal experience.


Use experience settings to change the settings for the custom portal
experience that you are working in. These settings affect how your users
interact with your portal experience, how your portal looks, and how
users navigate to and around your portal.


You must be in the correct application scope to edit experience settings.
If you are in a different scope, the experience settings are read-only.
To change your application scope, in the main header, select the


application picker ( ), and then select the application scope
that you want. For more information about the application scope, see
Learn about security and roles.


Learn how to change the following portal experience settings.


**•** Modify or add portal general settings for your portal experience.
Change the title of your portal, the description, and the path of the
portal.


**•** View the brand and theme setting in your portal experience to see the
theme currently assigned to your experience. The theme sets the look
and feel of the experience.


**•** Use portal navigation and menu settings to set up the navigation and
menu settings in the app shell of your portal experience. The app shell
is the wrapper of the portal contents. For example, the app shell can
show things like the logo of your company, user preferences, the search
icon, the configuration icon, and the user menu. For more information
about app shells, see Define UI experiences using app shells.


**•** Modify the portal search settings to show or hide the global search
functionality on public or private pages in your portal experience.


Experience settings for portals

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-149-1.png)


**•** Change the general settings in your portal experience


Change the general settings for your custom portal experience in UI
Builder. For example, you can modify the title, description, and path for
your portal experience.


**•** View the brand and theme setting in your portal experience


View the theme setting for your portal experience in UI Builder. The
theme sets the visual style of the experience and provides a consistent
look and feel across all pages.


**•** Change the navigation and menu settings in your portal experience


Change the header, footer, and menu settings for your custom portal
experience in UI Builder to fit the needs of your organization.


**•** Show or hide the search settings for your portal experience


Show or hide the global search functionality on the public or private
pages for your custom portal experience in UI Builder so that your users
can search on the portal.


Change the general settings for your custom portal experience in UI
Builder. For example, you can modify the title, description, and path for
your portal experience.


**Before you begin**


You must be in the correct application scope to edit the experience
settings. If you're in a different scope, the experience settings are readonly. To change your application scope, go to the main header, select


the application picker ( ), and then select the application
scope that you want. For more information about the application scope,
see Learn about security and roles.


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open a portal experience to work in or create an experience by
selecting **Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Select **Settings** in the UI Builder header.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-151-1.png)


4. Change the title, description, and path of your portal experience.


**•** The title lets everyone know what the workspace is called. Take
care when choosing a name for your workspace.


**•** The description lets your users know the details of the workspace.


**•** The path must be unique. The path can include digits (0-9), letters
(A-Z, a-z), and a few special characters ( `"-"`, `"."`, `"_"`, or `"~"` )
with the words separated by a forward slash or hyphen.


UI Builder experience settings

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-152-1.png)


5. (Optional) Select **Advanced settings** to edit the workspace record on
the ServiceNow AI Platform.


a. Update the record in the platform when you are finished.
When you go back to your workspace experience settings in
UI Builder, you see the changes that you made to the general
settings.


6. Click **Save** .


**Result**


When you go back to your portal experience settings in UI Builder, you
see the changes that you made to the general settings.


View the theme setting for your portal experience in UI Builder. The theme
sets the visual style of the experience and provides a consistent look and
feel across all pages.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open a portal experience to work in or create an experience by
selecting **Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select **Settings** in the UI Builder header.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-153-1.png)


4. Scroll to the **Branding and theming** section and note what is listed in
**Themes** .


By default, the Polaris theme is applied to UI Builder experiences.


**What to do next**


**• Theme Builder** enables you to create, edit, manage, and apply
Next Experience themes using a friendly visual interface. For more
[information, see Configuring Next Experience with Theme Builder.](https://www.servicenow.com/docs/csh?topicname=configuring-next-experience-with-theme-builder&version=zurich&pubname=zurich-platform-user-interface)


**•** If you are an admin user comfortable working in style records and JSON
code, you can create a custom theme to override the default Polaris
style. This option gives you the most control over typefaces, colors,
and images (including the banner and logo) in a theme. For more
[information, see Configuring Next Experience themes and preferences.](https://www.servicenow.com/docs/csh?topicname=config-next-experience-themes-prefs&version=zurich&pubname=zurich-platform-user-interface)


Change the header, footer, and menu settings for your custom portal
experience in UI Builder to fit the needs of your organization.


**Before you begin**


This task has the following prerequisites:


**•** You have an existing portal experience on UI Builder. For more
information, see Configure how users interact with your applications in
UI Builder.


**•** This workspace experience contains at least two pages.


**•** You want users to be able to navigate from a page to other pages that
you specify.


Role required: ui_builder_admin


**About this task**


Set up the navigation and menu settings in the app shell of your portal
experience. The app shell is the wrapper of the portal contents. For
example, the app shell can show things like the logo of your company,
user preferences, the search icon, the configuration icon, and the user
menu. You can configure this app shell in the ServiceNow AI Platform. For
more information about app shells, see Define UI experiences using app
shells.


You must be in the correct application scope to edit experience settings.
If you are in a different scope, the experience settings are read-only.


To change your application scope, in the main header, select the


application picker ( ), and then select the application scope.
For more information about the application scope, see Learn about
security and roles.


**Note:** For advanced information about
UX page properties, including JSON examples,
[see https://www.servicenow.com/community/next-experience-](https://www.servicenow.com/community/next-experience-articles/workspace-app-shell-ux-page-properties/ta-p/2331956)
[articles/workspace-app-shell-ux-page-properties/ta-p/2331956.](https://www.servicenow.com/community/next-experience-articles/workspace-app-shell-ux-page-properties/ta-p/2331956)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open a portal experience to work in or create an experience by
selecting **Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Select **Settings** in the UI Builder header.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-156-1.png)


4. To change the settings for the header, footer, and navigation menu
for the app shell of the portal experience you’re working in, select the
advanced settings links.


Portal experience settings for navigation


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-157-1.png)

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-157-2.png)


|Action|Procedure|
|---|---|
|Show the menu|a. To add a menu to your portal<br>experience, select**Navigation Menu**.<br>b. To remove the navigation menu,<br>deselect**Navigation Menu**.<br>c. To go to the ServiceNow AI Platform,<br>select**Advanced navigation menu**<br>**settings**. Here, you can change what<br>menu and menu items are displayed<br>in the navigation menu. For more<br>information, seeDefine UI experiences<br>using app shells.|
|Display a footer|a. To add a primary footer to your portal<br>experience, select**Primary footer**. The<br>footer can show a footer logo, content,<br>and other important links for your portal.<br>b. To go to the ServiceNow AI Platform,<br>click**Advanced navigation menu**<br>**settings**.<br>c. To add a second footer to your portal<br>experience, select**Secondary footer**.<br>A secondary footer includes additional<br>text links, social media elements, and<br>copyright information.|


5. Click **Save** .


Show or hide the global search functionality on the public or private
pages for your custom portal experience in UI Builder so that your users
can search on the portal.


**Before you begin**


Role required: ui_builder_admin


You can control whether the global search functionality is visible to users
of your portal experience. You can enable or disable the global search
for either public or private pages.


You must be in the correct application scope to edit the experience
settings. If you are in a different scope, the experience settings are readonly. To change your application scope, in the main header, select the


application picker ( ), and then select the application scope.
For more information about the application scope, see Learn about
security and roles.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open a portal experience to work in or create an experience by
selecting **Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Select **Settings** in the UI Builder header.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-160-1.png)


4. Scroll down to **Global search** .


5. Select the **Enable for public pages** or **Enable for private pages** to
show or hide the global search in public or private pages.
Portal search

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-160-2.png)


6. (Optional) Click **Advanced settings** to go to the ServiceNow AI
Platform to make changes to the application record on the
ServiceNow AI Platform®.
To enable or disable the search for a page, you must create a
separate UX Page property. The UX Page property overrides the
global search setting.


7. Click **Save** .

## **Define UI experiences using app shells**


Understand what app shells are, what app shells are available for UI
Builder, and why you would pick one over another.


**App shells**


An app shell is the wrapper of the contents of an experience page. An
app shell includes functionality similar to a web page. For example, an
app shell can show things in a header or footer of your experience,
such as a logo for your company, user preferences, a search icon,
configuration icon, user menu, and so on.


An app shell is required for UI Builder.


The app shell defines whether your experience has a workspace or portal
design. A workspace is a graphical user interface that puts multiple tools
on one page for handling requests from users. A portal is a page where
users can add requests, such as order items, track their tickets, and so on.


You choose which app shell to apply to your experience when you
create an experience in the ServiceNow® platform. For more information
on how to create an experience, see Configure how users interact with
your applications in UI Builder.


You can choose from various app shells when creating an experience.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-162-1.png)


**App shell descriptions**


|App shell|Description|Example|
|---|---|---|
|Breadcrumb<br>app shell|The breadcrumb app<br>shell includes a<br>header, breadcrumb style<br>navigation, and a primary<br>navigation bar for a<br>workspace experience. Use<br>the breadcrumb app shell<br>for focused workflows and<br>wizard flows that don't<br>require multi-tasking.||
|Header app<br>shell|The header app shell<br>includes a header and<br>user menu for a workspace<br>experience. Use the<br>header app shell for<br>experiences that require<br>minimal navigation and<br>few actionable items in the<br>header.||


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-162-2.png)

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-162-3.png)


|App shell|Description|Example|
|---|---|---|
|Portal app<br>shell|The portal app shell<br>includes the header and<br>footer for a portal<br>experience. The portal app<br>shell record is a reference<br>implementation of how the<br>menu, utilities, logo, and<br>login are configured for a<br>portal experience.||
|UXR Base<br>Experience<br>app shell|The UXR Base Experience<br>shell creates an experience<br>with the Next Experience<br>banner. The UXR Base<br>Experience shell provides<br>base functionality support<br>for experiences that are<br>configured within a parent<br>app, including experience<br>configuration, context<br>binding, routing, screen<br>loading, and caching. The<br>UXR Base Experience shell<br>has no visual or experience-<br>specific components. The<br>UXR Base Experience shell<br>can also be used for<br>experiences that have no<br>shell customization. For<br>example, Identity Center<br>directly uses UXR Base<br>Experience Shell as its app<br>shell.||


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-163-1.png)

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-163-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-164-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-164-1.png)
## Manage UI Builder pages and page variants

Learn what a page is in UI Builder. Understand the building blocks of a UI
Builder page, such as column layouts and components.


**UI Builder quick start**


Create pages in UI Builder as part of a workspace or custom portal
experience. UI Builder pages consist of layouts and components. You
build a page using column layouts and components to guide a user
through an experience. For example, you could build a page to manage
travel requests for your employees. The page could have column layouts
with components that contain lists of all travel requests submitted and
approved. You can add buttons that let users add and submit travel
requests. The way you build your page is limitless.


**Note:** One developer should work on any one variant at a time.


**Column layouts and components in UI Builder**


Column layouts and components are the building blocks of your UI
Builder page. Add column layouts and components to your page to
build or customize your workspace or portal experience. For example,
add a column layout and within a column place a button component
that lets users submit requests.


You can add column layouts, columns, and components, as well as
navigate between them, from the stage or the Content tree.


A column layout can contain one or more columns. Columns can
contain components. Change the visual styling of column layouts,
columns, and components to make it your own experience.


**Types of page layout elements**


|Type|Description|
|---|---|
|Column layout|A flexible container with one to six<br>columns. Add column layouts to<br>provide structure and a framework<br>for a page.|
|Column|Fill columns with components.|
|Component|Base elements of a page, such as<br>buttons, lists, and forms.|
|Modal|Use a modal to create a page<br>type in UI Builder that renders on<br>top of the page and requires<br>action.|
|Popover<br>|A popover is a type of container<br>that appears above a UI Builder<br>page when triggered by an event.<br>Use the popover component to<br>display additional information or<br>actions related to the page.<br>|


See Customize UI Builder pages using components for more information.


**Create a UI Builder page**


Create a UI Builder page to build a page experience from scratch or use
a page template. Build a page one component at a time. If you use one
of the pre-defined page templates, you start from a base structure and
can customize it to meet your needs.


Name your UI Builder page. Set the path (or keep the default path that
is automatically added based on your page name). A default path is


added based on your page name. You can also create your own path,
but the path must be unique. The **URL preview** shows the path of your

page.


The application scope protects applications by identifying and restricting
access to application files and data. The application scope defaults to
the scope that the user is currently in within the ServiceNow AI Platform®.
For more information about application scope, see Learn about security
and roles.


Use a UI Builder page template to create a page based on a predefined page template, and then customize the page to your needs.
You can reference or copy a page template. For more information, see
Create a page from a template.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-166-1.png)


**Create a UI Builder page: Advanced settings**


Add required parameters to your UI Builder page. A required parameter is
a piece of data that your page requires, such as a sys_id, table, or query.
Required parameters are useful for components as they can bind to the
value of the required parameter. For example, you can add a table
parameter to the URL field and then bind data to that table. When the
table is referenced, it exposes the table data to any components on the
page. Required parameters are visible in the URL when you add them to
your page. In the following example, a required parameter called table
was added. Notice it was appended to the URL.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-167-1.png)


Add optional parameters to your UI Builder page. Optional parameters
are optional pieces of data that you can add to the URL of your page.
Unlike required parameters, optional parameters are always name and
value pairs that work no matter what order they’re provided.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-167-2.png)


Set the audience and conditions settings for UI Builder page variants.
When you create a page, UI Builder also creates a variant of the page
for you by default. A page variant is a variation of your page at the same
path that lets you target experiences for different audiences using user
criteria. For example, a page for managers, and a variant of that page
for the manager's direct reports. For more information about creating a
variant, see Create a page variant.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-168-1.png)


For more information about audiences, see Learn about audiences.


**Test values in UI Builder**


Add a test value to your UI Builder page as a way to bring test data
into the page for testing purposes. For example, if you add a table as a
required parameter, you could add a test value of incident and bind a
data resource to it to bring in test data on the incident for that table.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-169-1.png)


To get test values to show data, add a data resource, then configure the
data resource to bind a record to the test value in the URL. For example,
you could add `incident` as a test value. Then add a data resource
named **Look up a single record** . In the **Table field**, dynamically bind the
incident test value to a `context.props.table` table, as shown in the
following image.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-170-1.png)


**View an existing UI Builder page**


You can work in any UI Builder page in your experience based on your
role settings. Click on the name of the page you want to work in while in
the experience view of your experience.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-171-1.png)


While in the page editor, open a different page variant by selecting the
drop-down in the header.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-172-1.png)


**Create a UI Builder page variant**


A variant lets you target different audiences with different content, using
user criteria. For example, you can create a homepage for agents, and
a variant of the page for managers that exists at the same URL path.


You set the audience for each UI Builder page variant. The audience
determines who uses the page variant. For example, if you create a
travel request page, create a variant of that page for managers to
manage the employee travel requests. You set the audience for the
manager page for anyone in the manager role. Employees cannot view
that variant. For more information about audiences, see Learn about
audiences.


See Create a page variant for more information.


**Edit UI Builder page settings**


Change the settings of your UI Builder page at any time by selecting
**Settings** in the UI Builder experience view. You can change the name,
path, and parameters of your page after you create a page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-173-1.png)


See Edit a page for more information.


**UI Builder Content tree**


The content tree in the page management panel is important. It not only
shows every column layout, column, and component on your UI Builder
page, it lets you easily find your components and work with them. The
content tree is especially important when you have multiple components
on your page. You select the component in your content tree to highlight
the component on the page, making it easier to build your page.


Content tree with components

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-174-1.png)


When you click a component in the content tree, it highlights the
component on your stage so you can configure, add styling, events,
data, and so on. You can drag items in the content tree to reorganize

your page.


It’s important to add a component label when you add a component to
your page. The component label is used in the content tree to apply
labels IDs to each component in the content tree. You can identify
the components much easier in the content tree when they're labeled
appropriately.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-175-1.png)


**UI Builder Toolbox**


Use the UI Builder toolbox to add layouts and components to your page.
Access the UI Builder toolbox by selecting **+ Add content** or the **+** icon in
the stage.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-176-1.png)


Search the toolbox to find layouts and components that you want to add
to a UI Builder page.


View a brief description of a layout or component by selecting the

information icon to view the tooltip. The components tab displays
different colors if a component can use a preset or is bundled with
multiple components.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-177-1.png)


**UI Builder Stage**


The stage is the largest area in the UI Builder editor and is used for
building pages. Add your column layouts and components here by either
selecting a + button, or dragging from the Component pane to the

page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-178-1.png)


On the stage, the body, column layouts, and columns are outlined in
magenta. Components are outlined in blue.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-179-1.png)


Use the Tree item icon to navigate to a different layer of content. For
example, if a column is selected, easily navigate to the parent column
layout or a component within the column.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-179-2.png)


Select the Menu icon on a column layout or component for options such
as duplicate and delete.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-179-3.png)


Changes made on the stage are reflected in the Styles panel at right.
Changes made in the Styles panel immediately update the elements on
the stage.


**Scale the size of the stage in UI Builder**


Adjust the size of the stage in the UI Builder editor by selecting the Width
drop-down.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-180-1.png)


**Undo and Redo in UI Builder**


Undo and redo changes you've made to your UI Builder page. Reverse
any action you make to a page layout, component, style or layout.


The undo and redo function can be found in the header toolbar. You


can select the undo ( ) or redo ( ) button to reverse an action.
You can also click the undo drop down to go back multiple steps. You
cannot undo and redo changes made in the data shelf.


You can undo the previous 20 actions by selecting the undo drop-down.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-181-1.png)


**UI Builder Configuration panel**


Use the configuration panel to work with components, including
arranging, styling, and setting up event handlers.


**•** Select the **Config** tab to configure components. Each component has
different configuration options that let you control the necessary parts
of the component. For example, a button component is simple, and
you can only configure its appearance, label, and a few properties. A
list component is more complicated, and contains dozens of editable
list parameters.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-182-1.png)


**•** Select the **Styles** tab in the configuration panel to add styling to a
component. You can use standards-based Cascading Style Sheets
(CSS) to change the visual style of a component. For example, add
or change a background color, a border, or any other CSS style.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-183-1.png)


See Change the default appearance of components for more
information.


**•** Select the **Events** tab to configure events that add actions to your
components, pages, data resources, and declarative actions. When
you add components to your UI Builder page, they are not configured
to perform any action. For example, a button component is static and
does not do anything until you bind an event action to it, such as
deleting a record.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-184-1.png)


See Manage actions in UI Builder pages for more information.


**•** Column layouts govern how components are arranged on a page.
When you add a column layout to a UI Builder page, you can configure
how you want the layout designed. After you add a component
to a column in the layout, you can configure the elements in more
advanced ways. For example, you can justify the content, align items,
and set the height, width, margins, background, borders, and padding
of your column layout, columns, and components. CSS grid is the most
powerful layout system. CSS Grid is built on top of a two-dimensional
grid that gives you power over how you create your pages.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-185-1.png)


See Organize components in UI Builder pages for more information.


**Open a UI Builder page to preview it**


Preview a UI Builder page to see what the page looks like as a web

page.


Select the button to test the variant that you're currently
working on, including modals, viewports, components, data resources,
and dynamic data. Previewing a page variant is useful for seeing how it
looks and functions while building an experience.


Another method of previewing a page is to request the URL path from
the server. Use this method to test if a user sees the variant when
they open the page. Select the drop-down arrow next to **Preview** and


select **Open URL path** or select **Preview** **> Open URL path**


.


See Learn how to view and test your UI Builder experience for more
information.


**Developer editing in UI Builder**


From the Menu, edit the UI Builder page as a developer on the platform.
This option lets you change the platform-level details of your page and
takes you out of UI Builder. You must have the proper role as a developer.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-186-1.png)


**•** Create a page in UI Builder


Create a page in UI Builder for a portal, workspace, or custom
application so that you can build a web experience for your users.


**•** Edit a page


Edit a page to change the page name, path, and parameters.


**•** Add an audience to your UI Builder page


Add one or more audiences to your page or page variant.


**•** Test values in a page


Add test values to your URL as a way to bring test data into a page.


**•** Create a page variant


A page variant in UI Builder is a variation of a page that exists at the
same path that targets different audiences using user criteria.


**•** Use pages across experiences


Use pages created in one in experience in another without needing to
rebuild the page.


**•** Responsive authoring


Use responsive authoring to create UI Builder pages that adjust
smoothly to different form factors (sizes), such as desktop, tablet, and
mobile.


**•** Learn how to view and test your UI Builder experience


Preview your experience in UI Builder to see how it looks and functions
while building an experience. Previewing helps ensure that your
experience works as expected, that the data resources are available,
and that the layouts are set up correctly.

## **Create a page in UI Builder**


Create a page in UI Builder for a portal, workspace, or custom
application so that you can build a web experience for your users.


**Before you begin**


Role required: ui_builder_admin


**About this task**


A page has a collection of components that make up a workspace,
portal, or custom application user interface (UI).


UI Builder

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-188-1.png)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select the **Create new page** in the center of the screen.


4. Select **Create from scratch instead** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-189-1.png)


You can also create pages using page templates, see Create a
page from a template for more information.


**Note:** As of Xanadu Store Release 1, responsive authoring is
available when creating a new UI Builder page from scratch.
Responsive authoring is not available for existing pages or pages
created with a template, however, these types of pages will
continue to use the existing, default reflow model. For more
information, see Responsive authoring.


5. Enter a unique name for the page in the **Name** field.


6. Specify a path for your page in the **URL Path** field. UI Builder
generates a default path based on the name that you provided in
the previous step.
A default path is added based on your page name. You can also
create your own path. The path is required and must be unique. The
path can include digits (0-9), letters (A-Z, a-z), and a few special
characters ( `"-"`, `"."`, `"_"`, `"~"` ), with the words separated by a
forward slash or hyphen. The **URL preview** shows the path of your

page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-190-1.png)


**Note:** The application scope defaults to the scope that the
user is currently in within the ServiceNow AI Platform®. For
more information about the application scope, see Learn about
security and roles.


7. Select **Continue** .


8. Add required parameters to your page URL.


a. Click **+ Add** .


b. Enter the required parameters for your page.
A required parameter is a piece of data that your page requires,
such as a sys_id, table, or query. Required parameters are useful
for components, because they can bind to the value of the
required parameter.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-191-1.png)


For more information, see Manage UI Builder pages and page
variants.


9. (Optional) Add optional parameters to the URL of your page.


a. Click **+ Add** .


b. Enter the optional parameters for your page.
Unlike required parameters, optional parameters are always
name and value pairs that work no matter what order that they
are provided in.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-191-2.png)


For more information, see Manage UI Builder pages and page
variants.


10. Select **Looks good** .


11. Enter a name for the page variant.


The form automatically contains **Default** but you can edit the page
variant name.


12. (Optional) Add one or more audiences for this page.
If an audience you need is not listed, you can choose the Open
audiences in platform link to create one.


13. (Optional) Declare conditions for when to display the page by either
using the provided dropdown menus or writing an encoded query
string.


[For more information on writing encoded queries, see Encoded query](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)
[strings.](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)


14. Select **Continue** .


15. Select the **Build responsive** option (default) for greater control of how
the page appears at different screen form factors or select **Build**
**without responsive** for automatic adjustment.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-192-1.png)


For more information, see Responsive authoring.


16. Select **Create** to create your blank page.
The page opens in Editor view so you can start adding content such
as layouts and components. For more information, see Customize UI
Builder pages using components.


**•** Create a page from a template


Use a template to create a page based on a pre-defined page
template. A page template can help you create pages faster and


keep pages consistent within an experience. Page templates may
include components, data resources, and a layout.


**•** Create a page from a legacy template


Use legacy page templates to reuse a page definition, such as record
or list page, for pages in your workspace or portal.


Use a template to create a page based on a pre-defined page
template. A page template can help you create pages faster and keep
pages consistent within an experience. Page templates may include
components, data resources, and a layout.


This video shows you how to perform the following procedure.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Select a page template when creating a page in your experience.
After creating a page from a template, you can customize the page
to your needs. Page templates include controllers that can be used with
component presets. See Bind data to UI Builder pages using controllers
(advanced feature) for more information.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select the **+** icon in the **Pages and variants** section.


4. Select **Create a new page** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-194-1.png)


5. Select **Use template** when pointing to the template that you want to

use.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-195-1.png)


6. Enter a unique name for the page in the **Name** field.


7. Specify a path for your page in the **Path** field. UI Builder generates a
default path based on the name that you provided in the previous
step.


A default path is added based on your page name. You can also
create your own path. The path is required and must be unique. The
path can include digits (0-9), letters (A-Z, a-z), and a few special
characters ( `"-"`, `"."`, `"_"`, `"~"` ), with the words separated by a
forward slash or hyphen. The **URL preview** shows the path of your

page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-196-1.png)


**Note:** The application scope defaults to the scope that the user
is in within the ServiceNow AI Platform®. For more information
about the application scope, see Learn about security and roles.


8. Select **Continue** .


9. Review the page parameters included in the template.
For more information about required and optional page parameters,
[see Adding Page Parameters in the ServiceNow Developer website.](https://developer.servicenow.com/dev.do#!/learn/courses/washingtondc/app_store_learnv2_uibuilder_washingtondc_ui_builder/app_store_learnv2_uibuilder_washingtondc_create_pages_in_ui_builder/UCP_AddingPageParameters_washingtondc)


10. Select **Looks good** .


11. Enter a name for the page variant.
The first variant you create is named **Default** by default.


12. Add one or more audiences for this page.
If an audience you need is not listed, you can choose the Open
audiences in platform link to create one.


13. (Optional) Declare conditions for when to display the page (this
variant) by either using the provided dropdown menus or writing an
encoded query string.


[For more information on writing encoded queries, see Encoded query](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)
[strings.](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)


14. Select **Create** to create your page from template.
The page you created displays in the **Page and variants** section of
your experience. Select **Editor** to start adding components to your
page. For more information, see Customize UI Builder pages using
components.


Use legacy page templates to reuse a page definition, such as record or
list page, for pages in your workspace or portal.


This video shows you how to perform the following procedure.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select the **+** icon in the **Pages and variants** section.


4. Select **Create a new page** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-198-1.png)


5. Select **Use template** when pointing to the template that you want to

use.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-199-1.png)


6. Enter a unique name for the page in the **Name** field.


7. Specify a path for your page in the **Path** field. UI Builder generates a
default path based on the name that you gave in the earlier step.
A default path is added based on your page name. You can also
create your own path. The path is required and must be unique. The
path can include digits (0-9), letters (A-Z, a-z), and a few special
characters ( `"-"`, `"."`, `"_"`, `"~"` ), with the words separated by a
forward slash or hyphen. The **URL preview** shows the path of your

page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-200-1.png)


**Note:** The application scope defaults to the scope that the user
is in within the ServiceNow AI Platform®. For more information
about the application scope, see Learn about security and roles.


8. Select how you want to use the base page template.
Select **Use the original page (customization limited)** if you want to
reference the template and its data. Select **Copy contents of the**
**page (fully customized)** to copy the contents of the page template.
When you reference a page template, your page automatically
updates when you upgrade to a new release. If you copy the page
template, your page will not update after upgrade.


9. Select **Continue** .


10. (Optional) Add required parameters to your page URL.


a. Click **+ Add** .


b. Enter the required parameters for your page.
A required parameter is a piece of data that your page requires,
such as a sys_id, table, or query. Required parameters are useful
for components, because they can bind to the value of the
required parameter.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-201-1.png)


For more information about required and optional page
[parameters, see Adding Page Parameters in the ServiceNow](https://developer.servicenow.com/dev.do#!/learn/courses/washingtondc/app_store_learnv2_uibuilder_washingtondc_ui_builder/app_store_learnv2_uibuilder_washingtondc_create_pages_in_ui_builder/UCP_AddingPageParameters_washingtondc)
Developer website.


11. (Optional) Add optional pieces of data that you want to add to the
URL of your page.


a. Click **+ Add** .


b. Enter the optional parameters for your page.
Unlike required parameters, optional parameters are always
name and value pairs that work no matter what order that they
are provided in.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-201-2.png)


For more information, see Manage UI Builder pages and page
variants.


12. Select **Looks good** .


13. Enter a name for the page variant.
The form automatically adds **Default** to the page name.


14. Add one or more audiences for this page.


If an audience you need is not listed, you can choose the Open
audiences in platform link to create one.


15. (Optional) Declare conditions for when to display the page by either
using the provided dropdown menus or writing an encoded query
string.


[For more information on writing encoded queries, see Encoded query](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)
[strings.](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)


16. Select **Create** to create your blank page.
The page you created displays in the **Page and variants** section of
your experience. Select **Editor** to start adding components to your
page. For more information, see Customize UI Builder pages using
components.

## **Edit a page**


Edit a page to change the page name, path, and parameters.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Edit page settings to change the name and path of your page. This is
useful if you decide the name or path should be changed after you
create the page. If your page is in a different application scope, you can
choose to edit it in the original scope.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open the experience with the page that you want to edit.


3. Select **Settings** next to the page that you want to edit.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-203-1.png)


4. In the page settings window you can change the name, path, and
parameters of your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-204-1.png)


5. (Optional) Add required parameters to your page URL.


a. Click **+ Add** .


b. Enter the required parameters for your page.
A required parameter is a piece of data that your page requires,
such as a sys_id, table, or query. Required parameters are useful
for components, because they can bind to the value of the
required parameter.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-205-1.png)


For more information, see Manage UI Builder pages and page
variants.


6. (Optional) Add optional pieces of data that you want to add to the
URL of your page.


a. Click **+ Add** .


b. Enter the optional parameters for your page.
Unlike required parameters, optional parameters are always
name and value pairs that work no matter what order that they
are provided in.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-206-1.png)


For more information, see Manage UI Builder pages and page
variants.


7. Click **Save** .

## **Add an audience to your UI Builder page**


Add one or more audiences to your page or page variant.


**Before you begin**


Role required: admin


The glide.ux.user_criteria_enabled property needs to be set to **true** to
configure access for users based on role, department, group, location, or
company. See Enable the user criteria property, for more information.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open the experience with the page that you want to edit.


3. Select **Settings** next to the page variant that you want to edit.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-207-1.png)


4. In the page variant settings window, select **Edit all audiences** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-208-1.png)

5. Click **+ Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-209-1.png)

6. Select an audience in the audience field.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-210-1.png)


**Note:** If an audience you need is not listed, you can choose the
**Open audiences in platform** link to create one.


7. Set the order of the audiences.


**Note:** To give higher priority to an audience, enter a lower
number. If a user is part of multiple audiences, the audience with
the highest priority is used.


8. Check **Active** if you want the audience to be able view the page.


9. Select **Save** .
The audience displays in the **Audiences** list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-211-1.png)


10. Select **Done** .


**•** Enable the user criteria property


Enable the user criteria property to configure access for users based on
role, department, group, location, or company in UI Builder.


Enable the user criteria property to configure access for users based on
role, department, group, location, or company in UI Builder.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > sys_properties.list** .


2. Select the glide.ux.user_criteria_enabled property.


3. In the **Value** field, specify **true** .


4. Click **Update** .


**What to do next**


Add audiences to your pages in UI Builder. For more information, see Add
an audience to your UI Builder page.

## **Test values in a page**


Add test values to your URL as a way to bring test data into a page.


Use test values to give values for required and optional URL parameters
as a way to test your page with actual data.


Test values are important because you can use them to simulate
how your page behaves when the page gets its required or optional
parameters from the URL. A UI Builder URL is not the same as the URL
when you preview your page. So, UI Builder needs a way to simulate
what happens to the page during different states of the preview URL.


For example, say that you’re building a record page that displays a form
for a single record. For the record page to load, the page must have a
<table> and <sysId> in the URL so that it can get and display the proper
record. In UI Builder, you must supply test values for the table and sys_id
so that you can see how the page looks when you preview the page.


To get test values to show data, add a data resource, then configure the
data resource to bind a record to the test value in the URL. For example,
you could add `incident` as a test value.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-213-1.png)


Then add a data resource named **Look Up Record** . In the **Table field**,
dynamically bind the incident test value to a `context.props.table`
table, as shown in the following image.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-214-1.png)

## **Create a page variant**


A page variant in UI Builder is a variation of a page that exists at the
same path that targets different audiences using user criteria.


This video show you how to perform the following procedure.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Learn how to create a page variant in UI Builder. A page variant is
based on your page with content targeted for a different audience. For
example, you can create a homepage for agents, and a variant of that
page for managers of those agents. The variant exists at the same URL.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-216-1.png)


**•**


**•**


**•**


When someone who is part of the application admins audience
accesses the page URL, the user sees a version of the page that has
application admin-specific details, such as application metrics and
usage details. For the Special Occasions application the page would
show how many users have birthdays and work anniversaries and how
many do not. The page would also show how many issues have been
reported with special occasions.


When someone who is part of the department managers audience
accesses the page URL, the user sees department-related information
for the application, such as people in their department with upcoming
birthdays and work anniversaries, and whether or not those people are
okay with their special occasions being shared.


When someone who is part of the application users audience accesses
the page URL, the user sees a user-specific version of the page with


their special occasions that allows them to configure whether or not
they want others to see their special occasions.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open the experience with the page for which you want to create a
variant.


3. Select the **+** icon in the **Pages and variants** section.


4. Select **Add a variant to a page** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-217-1.png)


5. Click **+ Add variant** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-217-2.png)


6. Click **Build from scratch instead** or select **Use template** when pointing
to the template that you want to use.


7. Enter a name for the variant page.


The name can be similar to your page name, or what ever you want
it to be.


**Note:** The application scope defaults to the scope that the user
is in within the ServiceNow AI Platform®. For more information
about application scope, see Learn about security and roles.


8. Specify one or more audiences for your variant page by selecting
**Add an audience** .
The audience is important because it lets you assign your page
variant to a specific role or group. If an audience you need is not
listed, create one by selecting **View all available audiences**, and
then selecting **New** .


9. Declare conditions for when to display the page by either using the
provided dropdown menus or writing an encoded query string.


To learn more about declaring conditions, see Control the conditions
for a page variant. For more information on writing encoded queries,
[see Encoded query strings.](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)


10. If creating a page from scratch, select **Continue** and then select the
**Build responsive** option (default).


11. Click **Create** to create your page variant.


**•** Edit page variant settings


Edit page variant settings to add additional criteria to determine when
the page variant displays to users.


**•** Control the conditions for a page variant


Set the conditions and manage the criteria that determine when a
page variant is displayed. UI Builder page variants enable you to create
different versions of a page to tailor content for a specific audience.


Edit page variant settings to add additional criteria to determine when
the page variant displays to users.


**Before you begin**


Role required: admin


**About this task**


Customize page variant settings to set who sees the page variant. You
can add and remove audiences as well as edit conditions to determine
when a page variant is shown. Conditions can only evaluate the listed
parameters. Conditions are based on setting an order and adding a
query string that sets the criteria that must be met for the page variant
to display. If you have multiple page variants that all have the same
conditions, then the variants go by the order setting. The following task
shows how to set the variant conditions and order.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open the experience with the page variant that you want to edit.


3. Select **Settings** next to the page that you want to edit.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-219-1.png)


4. On the form, fill in the fields.


**Field** **Description**


|Name|Enter a name for the page variant.|
|---|---|
|Availability|Select**Active** to make the page variant<br>viewable to the selected audience.|
|Order|Add an order for the condition in the**Order**<br>field. You may want certain conditions to have<br>a higher priority than others. The lower the<br>number, the higher the priority.|
|Conditions|Set the rules for when your pages are<br>shown. For more information, seeControl the<br>conditions for a page variant.|
|Audiences|Add or remove audiences for the page<br>variant. For more information, seeLearn about<br>audiences.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-221-1.png)


5. Click **Save** .


Set the conditions and manage the criteria that determine when a
page variant is displayed. UI Builder page variants enable you to create
different versions of a page to tailor content for a specific audience.


**Before you begin**


Role required: ui_builder_admin


**About this task**


If you have multiple page variants that all have the same conditions, the
variants go by the order setting.


**Procedure**


1. Create a page variant.


For more information, see Create a page variant.


2. Set the conditions for a new variant.


In this example, you configure a page variant to display when you
open a record from the Task table.


a. On the **First, select a template** screen, locate the **Standard record**
template and select **Use template** .


**Note:** Conditions can only evaluate parameters that have
been added. In this example, the **Standard record** template
includes the table and sys_id parameters.


b. Enter a name for your page and select **Continue** .


c. Review the URL parameters and select **Looks good** .


Notice that table and sysId are added as required parameters,
which appear in the URL preview.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-222-1.png)


d. On the **Tell us about your variant** screen, enter a name for your
variant.


e. In the form section, fill out the fields.


**Variant condition form section**


|Field|Description|Example|
|---|---|---|
|Parameter|The aspect or<br>attribute that you<br>want to check.|table, sys_id<br>**Note:**<br>Conditions can<br>only evaluate<br>the added<br>parameters.<br>However,<br>conditions<br>written for<br>subpages<br>inherit<br>additional<br>outputs from<br>the parent<br>page<br>controllers,<br>providing a<br>wider range of<br>parameters<br>options.|
|Operator|The rule that<br>compares the<br>parameter to the<br>value. It tells<br>you how the<br>comparison is<br>made.|**is**, **is not**, **starts with**|
|Value|The number, text,<br>or option input<br>that you want to<br>compare with the<br>parameter.|"`Incident`",<br>"`12345`", "`Active`",<br>"`Change Request`"|


**Note:** The table and sysId parameters are available options
for the **Parameter** field because they're required parameters
as a part of the **Standard record** template.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-224-1.png)


f. Select **Create** .


3. Review the conditions created for your variant.


a. In the Experience view, find the variant for which you want to
view the conditions.


b. Select the **View** button to display the conditions set for that
variant.


4. Edit the existing conditions for your variant.


a. From the Experience view, find the variant for which you want to
edit the conditions.


b. Select **Settings** .


c. Under Conditions, select **Edit conditions** .


The condition you previously set appears. You can update these
fields.


d. On the **Edit variant conditions** screen, next to the condition,


select the **and** ( ) or **or** ( ) button to add another
condition and specify the criteria.


For example, by adding the following **AND** condition ( **[sysId]**

**[is]** `[abcd1234]` ), you configure the page variant to display
when you access a record from the Task table with a sys_id of
abcd1234.


**Note:** You can add **AND** or **OR** conditions. To mix both
types, you must write an encoded query.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-225-1.png)


e. (Optional) Select **Enter as text** to write an encoded query that
specifies the criteria.


The **Edit variant conditions** screen displays the encoded query
field, where the conditions you previously set are shown in
encoded query form: `table=task^sysId=abcd1234` .


For example, by adding the following 'OR' condition
( `^ORsysId=efgh5678` ), you set the page variant to display when
you access a record from the Task table with a sys_id of either
abcd1234 or efgh5678. For more information on writing encoded
[queries, see Encoded query strings.](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-226-1.png)

## **Use pages across experiences**


Use pages created in one in experience in another without needing to
rebuild the page.


**Benefits of sharing pages across experiences**


Using pages across experiences lets page builders and admins share
and reuse pages across workspaces, eliminating the need to create and
manage duplicate copies of a page. Users can engage with shared
pages consistently, without switching experiences. This feature reduces
operational overhead, increases flexibility, and enhances consistency,
helping allocate resources better and empower teams to innovate
efficiently.


Sharing pages across experiences allows users who operate out of
multiple workspaces to utilize a page from one workspace into another
instead of duplicating content. This improves usability, reduces context
switching, and ensures consistency across workspaces. It also simplifies
maintenance, since updates to a shared page are reflected across all
experiences where it’s used, saving time and reducing the risk of errors.


**Viewing shared pages in Experience View**


Pages that can be used across experiences display a blue icon
containing two pages in UI Builder's experience view. You can select the
icon to go to the **UX App Route** settings page on the platform where
you can enable or disable the ability to use the page across experiences.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-227-1.png)


Reusable pages added to your experience display the name
of their source experience. Click the icon next to the
page title to view details about the page, access the


original experience, adjust page settings, or explore linked pages.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-228-1.png)


**Limitations**


When sharing a page, you must also specify all the linked pages
associated with it. **Linked pages** are pages whose routes are tied to the
same source experience. This is required so that the experience receiving
a shared page has references to all necessary outbound pages.


**Note:** Shared pages can only be configured in the ServiceNow®
platform currently. However, you can view these pages while in the
Experience View of UI Builder.


**Enable pages to be used across experiences**


Select pages that you want to share across experiences in UI Builder.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select **View experience settings** .


4. Select **Open app config** .
The UX App Configuration tab opens.


5. Select the page you want to use across experiences.


6. Select the **Use across experiences** box.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-230-1.png)


7. Select **Update** .

## **Responsive authoring**


Use responsive authoring to create UI Builder pages that adjust smoothly
to different form factors (sizes), such as desktop, tablet, and mobile.


**Responsive authoring in UI Builder**


Responsive authoring enables you to create pages that look good and
function properly at any form factor, making it easier for people to
interact with the content. For example, a page containing three columns


when viewed on a laptop, can adjust to a single column for smaller

screens.


UI Builder currently offers three default form factors:


**•** Desktop (1281 pixels to infinity)


**•** Tablet (1280 pixels and smaller)


**•** Mobile (500 pixels to zero)


In addition to these form factors, you can create up to three additional
custom breakpoints (widths). For more information, see Create a
breakpoint for responsive authoring.


There are different techniques for editing pages so they're usable at
different form factors. Use any of the following options:


**•** Show or hide components


**•** Change component configuration


**•** Edit styles


**•** Rearrange the layout


**Responsive authoring and reflow**


As of Xanadu Store Release 1, responsive authoring is only available
when creating UI Builder pages from scratch. Responsive authoring isn't
available for existing pages or pages created with a template. These
types of pages continue to use the existing, default reflow model to
adjust pages for different screen widths.


Reflow transforms page layouts into a vertical, stacked view
automatically without loss of content or functionality when users increase
browser zoom to 400%. This adjustment helps users with low vision or
who have trouble seeing web content in a browser due to monitor size,
device type, poor lighting, or other situations.


All existing pages that were created with templates or from scratch
use reflow automatically. Now, when creating pages from scratch in UI
Builder, an extra step shows you that responsive authoring is selected by
default. You can choose to use reflow instead by selecting **Build without**
**responsive**, however, using the responsive authoring option gives you


more control over how pages work and look at different form factors. For
more information about creating pages in UI Builder, see Create a page
in UI Builder.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-232-1.png)


[For more information about reflow, see Reflow for Configurable](https://www.servicenow.com/docs/csh?topicname=auto-reflow&version=zurich&pubname=zurich-platform-user-interface)
[Workspace.](https://www.servicenow.com/docs/csh?topicname=auto-reflow&version=zurich&pubname=zurich-platform-user-interface)


For a list of UI Builder components that support reflow, see the **Support for**
**reflow** [section of the Next Experience Components release notes.](https://servicenow.com/docs/bundle/washingtondc-release-notes/page/release-notes/now-platform-app-engine/component-rn.html)


**Application and cascading of changes**


All changes made to a form factor are applied to all smaller form
factors automatically. For example, any changes made to tablet apply
to both tablet and mobile. However, if you then make changes to the
mobile form factor, it overrides the cascaded settings from the tablet
form factor. This cascading functionality enables you to make specific
changes for each smaller form factor so the page looks and functions
well.


**Note:** Changes don't cascade up to larger sizes. For example,
changes made to tablet aren't applied to the desktop.


**Responsive authoring and controllers**


If you add a controller to a page, the controller properties are global and
cannot be set per form factor. For more information about controllers,
see Bind data to UI Builder pages using controllers (advanced feature).


**Using responsive authoring as you create pages**


As you build pages, create tailored designs to control the look and feel
for different form factors.


By default on the stage, you build pages for the desktop (1281 pixels to
infinity). At any time, select another icon to see the page on the stage
at a different form factor, such as tablet or mobile. As needed, edit the
page so it displays appropriately at the new form factor.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-233-1.png)


Here's what a sample page looks like at the desktop form factor.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-233-2.png)


Here's the same page customized for the tablet form factor.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-234-1.png)


For tablet, the heading and image components have been reduced in
size. The simple list component configuration was edited to show four
columns instead of six and the maximum number of rows was set to
5. When editing a component for a form factor, the fields that have
changed are marked with a cascading icon for that form factor (in
this case, tablet). The icon enables you to determine the differences
between the form factors for a given page easily.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-235-1.png)


Here's the same page customized for the mobile form factor.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-236-1.png)


The number of words in the heading was reduced and the image
component was hidden. The simple list component configuration was
edited to show two columns instead of four and the option to hide
the "view all" footer option was selected. The two fields customized
specifically for mobile have a mobile cascading icon next to them. The
**Maximum rows** field still retains the tablet cascading icon because that
field is inheriting the tablet setting and wasn't customized for mobile.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-237-1.png)


In addition to the default form factors in the editor view, at any time
you can manually enter a number in the pixel field. The stage adjusts to
the nearest form factor based on range. For example, entering 850 pixels
adjusts the stage to the tablet form factor because its range is defined as
1280 to 501 pixels.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-237-2.png)


**Note:** Form factors and the ability to enter a pixel width are also
available when previewing a page. For more information, see Learn
how to view and test your UI Builder experience.


**•** Adjusting component visibility in responsive authoring


When creating pages with responsive authoring for different form
factors, learn how to show or hide components by completing steps
to hide an image at mobile size.


**•** Configuring components for responsive authoring


When creating pages with responsive authoring for different form
factors, learn how adjusting some component configuration options
can make pages look and work better at smaller sizes.


**•** Adjust styles for responsive authoring


When creating pages with responsive authoring for different form
factors, learn how to change style options to increase the usability of
the page at smaller sizes.


**•** Adjust layout for responsive authoring


When creating pages with responsive authoring for different form
factors, learn how to adjust the layout to improve the look and feel
of the page at smaller sizes.


**•** Create a breakpoint for responsive authoring


Learn how to create custom breakpoints for responsive authoring to
control the look and feel of a page at different form factors.


When creating pages with responsive authoring for different form factors,
learn how to show or hide components by completing steps to hide an
image at mobile size.


**Before you begin**


Role required: ui_builder_admin


**About this task**


A method of increasing page usability is to hide components or show a
different component across breakpoints. There are countless ways to use
component visibility, but a few examples include:


**•** Use multiple button components horizontally across the top of a page
for desktop and tablet size, but at mobile size, hide the buttons and
show the dropdown component.


**•** Use a smaller button size for mobile size, but check that the buttons are
large enough for users to press with a thumb. Consider changing the
placement of buttons for mobile as well.


**•** Use images in desktop and tablet pages, but hide images, especially
larger ones, in mobile.


In this procedure, show buttons across the top for the desktop and tablet
form factors, but hide the buttons and use the dropdown component for
mobile.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page from scratch with responsive authoring.
For more information about how to create a page, see Create a
page in UI Builder.


4. At the top, check that the desktop form factor icon is selected.


5. Add a column layout by selecting **+ Add content** under **Body** in the
content tree.


6. On the **Layouts** tab, select **Single column** .


7. Add the first button component.


a. Select the **+** icon in the center of the new column on the stage.


b. On the **Components** tab, find and select the **Button** component.


c. In the configuration panel, select **None - Configure the**
**component manually** .


d. In the configuration panel, on the **Configure** tab, replace the
default text in the **Label** field by entering `Tasks` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-240-1.png)


e. Select **Save** .


8. Add two more buttons by repeating step 7 twice and in 7d name the
buttons `Incidents` and `Changes` .


**Note:** To add the buttons, point to **Button 1** in the content tree,
select the menu icon, and then select **Add after** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-241-1.png)


9. Check that the content tree and page are accurate.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-241-2.png)


10. Add some space around each button.


a. In the content tree, select **Button 1** .


b. In the configuration panel, select the **Styles** tab.


c. In **Spacing**, select **Margin** .


d. In the menu, select **XS** (extra small).

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-242-1.png)


e. Select **Save** .


11. Add space around the other two buttons by repeating step 10 for
each.


12. Change the buttons from the vertical direction to the horizontal
direction.


a. Select **Column 1** in the content tree.


b. On the configuration panel, in **Direction**, select the row icon.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-243-1.png)


c. Select **Save** .
The page looks good at desktop width.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-243-2.png)


13. Select the tablet form factor icon.


The spacing and position of the buttons also looks good at tablet
width.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-243-3.png)


14. Select the mobile responsive authoring icon.


The buttons use almost all the horizontal space at the smaller size.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-244-1.png)


15. Add the dropdown component.


a. Select the desktop form factor at the top of the stage.


b. Point to **Button 3** in the content tree, select the menu icon, and
then select **Add after** .


c. On the **Components** tab, find and select the **Dropdown**
component.


d. In the configuration panel, select **None - Configure the**
**component manually** .


e. In the configuration panel, on the **Configure** tab, remove the
default text in **Placeholder text** and select **menu-outline** in **Icon** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-245-1.png)


f. Select **Save** .


16. Hide the dropdown component at the desktop and tablet form
factors.


a. In the content tree, select **Dropdown 1** .


b. In the configuration panel, on the **Configure** tab, select
**Component visibility** to show the options.


c. Select **Hide component** .


d. Select **Save** .


17. At the mobile form factor, hide the button components.


a. Select the mobile form factor icon at the top of the stage.


b. In the content tree, select **Button 1** .


c. In the configuration panel, on the **Configure** tab, select **Hide**
**component** .


d. Repeat steps b-c for **Button 2** and **Button 3** .


e. Select **Save** .
Two locations show that the button components are hidden at
mobile size. First, in the configuration panel, next to the **Hide**
**component** option, select the mobile icon. A message is displayed
to confirm that the value (hide component selected) is for the mobile
size.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-246-1.png)


Second, in the content tree, the three button components are


displayed with the hidden icon.


18. At the mobile form factor, show the dropdown component.


a. In the content tree, select **Dropdown 1** .


b. In the configuration panel, on the **Configure** tab, select **Hide**
**component** to clear the field.


c. Select **Save** .


19. Select **Preview** .
The mobile form factor is displayed with the menu icon. If you select
the arrow, the default options are displayed (List item 1, List item
2, and so on). You would configure the dropdown component to
display **Tasks**, **Incidents**, and **Changes** just like the horizontal buttons
available at the tablet and desktop form factors.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-247-1.png)


20. Select the desktop and tablet form factor icons at the top.
The desktop and tablet form factors only show the horizontal buttons,
not the menu icon.


21. Close the preview overlay by selecting the **X** .


When creating pages with responsive authoring for different form factors,
learn how adjusting some component configuration options can make
pages look and work better at smaller sizes.


**Before you begin**


Role required: ui_builder_admin


**About this task**


A method of increasing page usability is to tailor the look and feel of
components using different configurations across breakpoints. There are
countless ways to use component configuration. In this procedure, edit


several configuration options for the List component to make it more
suitable for smaller form factors.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page from scratch with responsive authoring.
For more information about how to create a page, see Create a
page in UI Builder.


4. At the top, check that the desktop form factor icon is selected.


5. On the stage, select **+ Add content** .


6. On the **Layouts** tab, select **Single column** .


7. Add the list component by selecting the **+** icon in the center of the
new column.


8. On the **Components** tab, find and select the **List** component.


9. In the configuration panel, select **None - Configure the component**
**manually** .


10. View the page at the desktop form factor.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-249-1.png)


Note the elements displayed, including the icons at the top, the
number of columns, and the pagination information at the bottom.


11. Select the mobile form factor icon.


At the mobile form factor, the list component is crowded and
contains both vertical and horizontal scroll bars.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-250-1.png)


Make some simple configuration changes to improve the usability
and appearance for the mobile form factor.


12. Select **List 1** in the content tree.


13. In the configuration panel, on the **Configure** tab, find the **Number of**
**displayed columns** field and enter `1` .
Only the **Number** column is displayed. The horizontal scroll bar was
removed.


14. In the configuration panel, on the **Configure** tab, scroll down to make
the following changes in the **Header** section:


a. Change the **Size** to **Small** .


b. Select the **Hide last refresh information** option.


c. Select the **Hide list actions** option.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-251-1.png)


As you made each change, the stage updated automatically.
The header is a smaller size, the refresh time was removed, and
the list actions icon was removed.


d. Select **Save** .


15. On the stage, scroll to the bottom of the mobile view.


16. In the configuration panel, on the **Configure** tab, scroll down and
make the following changes in the **Pagination** section (if necessary,
select **Pagination** to expand the field):


a. Select the **Hide range** option.


b. Select the **Hide row count** option.


c. Select the **Hide rows per page selector** .


d. Select **Save** .
The range, row count, and rows per page selector were removed.
(The row count is still available at the top of the mobile screen).


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-252-1.png)


In the configuration panel, the options and fields you edited are
marked with the mobile cascade icon.


17. Select the mobile cascade icon next to any option or field to confirm
that the value is for the mobile form factor.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-252-2.png)


18. Select the tablet and the desktop form factor icons at the top to
confirm that no changes were made to the larger form factors.


When creating pages with responsive authoring for different form factors,
learn how to change style options to increase the usability of the page at
smaller sizes.


**Before you begin**


Role required: ui_builder_admin


**About this task**


A method of increasing page usability is to tailor components using
different styles across breakpoints. There are numerous options for
editing styles. In this procedure, edit the margin around the stylized text
component and reduce the text size so it uses less space on smaller form
factors.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page from scratch with responsive authoring.
For more information about how to create a page, see Create a
page in UI Builder.


4. At the top, check that the desktop responsive authoring icon is
selected.


5. On the stage, select **+ Add content** .


6. On the **Layouts** tab, select **Single column** .


7. Add the stylized text component.


a. Select the **+** icon in the center of the column on the stage.


b. On the **Components** tab, find and select the **Stylized text**
component.


c. In the configuration panel, select **None - Configure the**
**component manually** .


d. In the configuration panel, on the **Configure** tab, double-click (or
use the keyboard shortcut) in the **Text** field to select the default
text.


e. Replace the default text by entering `Critical Operations`
`Workspace Admin Center` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-254-1.png)


f. Select **Save** .


8. Add some space around the stylized text component and center it.


a. In the content tree, select **Stylized text 1** .


b. On the configuration panel, select the **Styles** tab.


c. In **Spacing**, select **Margin** .


d. Select **Large** in the list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-255-1.png)

e. In **Alignment**, select the center icon.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-256-1.png)


f. Select **Save** .
The stage updates automatically, showing the additional white
space around the stylized text component and centering it.


9. Select the tablet form factor icon.


The spacing and heading size of the stylized text component looks
good at tablet size.


10. Select the mobile form factor icon.


The stylized text component uses a great deal of vertical space at
the smaller size.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-257-1.png)


11. Remove the extra margin space and make the heading smaller just
for the mobile form factor.


a. In the content tree, select **Stylized text 1** .


b. On the configuration panel, select the **Styles** tab.


c. In **Spacing**, select **Margin** .


d. Select **0** in the list.


e. Select the **Configure** tab.


f. In **HTML tab**, select **H3** .


g. Select **Save** .
The stage updates automatically showing that the stylized text
component uses less space.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-258-1.png)


12. Select the tablet and the desktop form factor icons at the top to
confirm that no changes were made to the larger form factors.


When creating pages with responsive authoring for different form factors,
learn how to adjust the layout to improve the look and feel of the page
at smaller sizes.


**Before you begin**


Role required: ui_builder_admin


**About this task**


A method of increasing page usability is to tailor components by
adjusting the layout across breakpoints. There are numerous options for
adjusting the layout. In this procedure, adjust the layout of the tabs
component for the mobile form factor.


Most column layout options on the property pane can be edited for
different form factors. However, the following options have global values
across form factors:


**•** Number of columns


**• Stack columns below (pixels)** option


**•** All options under **Accessibility**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-259-1.png)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page from scratch with responsive authoring.
For more information about how to create a page, see Create a
page in UI Builder.


4. At the top, check that the desktop form factor icon is selected.


5. On the stage, select **+ Add content** .


6. On the **Layouts** tab, select **Single column** .


7. Add the tabs component.


a. Select the **+** icon in the center of the column on the stage.


b. On the **Components** tab, find and select the **Tabs** component.


c. Select **Save** .


8. In the configuration panel, on the **Configure** tab, edit the name of
the first tab by selecting the edit icon.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-260-1.png)


9. In **Tab label**, enter `Tab 1` .


10. In **Tab ID**, enter `tab_1`


11. Select **Save** .


12. Add a second tab.


a. On the **Configure** tab, select **+ Add** next to **Tabs** .


b. Select **Start from an empty container** and then select **Next** .


c. In **Tab label**, enter `Tab 2` .


d. Check that **Tab ID** has been automatically filled in with **tab_2** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-261-1.png)


e. Select **Create** .


13. Add a third tab by repeating step 12 and in 12c name the tab `Tab`

`3` .


14. Check that your content tree and page are accurate.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-262-1.png)


15. Select the tablet form factor icon.


The spacing and position of the tabs looks good at tablet width.


16. Select the mobile form factor icon.


The tabs take more space at the smaller size.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-263-1.png)


17. Change the layout of the tabs just for the mobile size.


a. In the content tree, select **Column 1** under **Column layout 1** .


b. On the configuration panel, in **Direction**, select the row icon.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-263-2.png)


c. Select **Save** .
The stage updates automatically showing that tab 1 is visible and
that there's a new dropdown menu.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-264-1.png)


18. Select **Preview** .


19. Select **More** .

The other two tabs are available.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-264-2.png)


20. Select the desktop and tablet form factor icons to see that the More
drop-down doesn't appear.


21. Select the **X** to close the **Preview** overlay.


Learn how to create custom breakpoints for responsive authoring to
control the look and feel of a page at different form factors.


**Before you begin**


Role required: ui_builder_admin


**About this task**


UI Builder currently offers three default form factors:


**•** Desktop (1281 pixels and larger)


**•** Tablet (1280 pixels and smaller)


**•** Mobile (500 pixels and smaller)


Add up to three additional breakpoints. For example, there's a default
form factor of 500 pixels and smaller for mobile devices, but you may
need a breakpoint of 360 pixels.


**Note:** Custom breakpoints represent a range. If you create a
breakpoint at 800 pixels, all changes apply to devices with a width
at and lower than the new size. For example, a page opened on
a screen 750 pixels wide uses the 800 pixel settings (properties and
styles) unless there's another custom breakpoint at 750 pixels.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open an existing page created from scratch with responsive
authoring or create a page from scratch with responsive authoring.
For more information about how to create a page, see Create a
page in UI Builder.


4. Select the menu icon next to the three form factor icons.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-266-1.png)


5. Select **+ Add breakpoint** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-266-2.png)


6. Type in a width (in pixels) and select **Add** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-266-3.png)


The new breakpoint is saved and appears as a form factor icon.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-266-4.png)


As you build the page, select any of the form factor icons to view
and edit the page at that size.


7. To edit or delete a custom breakpoint, select the menu icon, point to
the breakpoint name, and select the edit or delete icon.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-267-1.png)


**Note:** The default form factors (desktop, tablet, and mobile)
can't be edited or removed.

## **Learn how to view and test your UI Builder experience**


Preview your experience in UI Builder to see how it looks and functions
while building an experience. Previewing helps ensure that your
experience works as expected, that the data resources are available,
and that the layouts are set up correctly.


**Test your page**


You can test your page as the developer or see it as it would appear to
an end user. Previewing doesn't require saving first.


**Note:** Previewing inactive variants and page collections (sub
pages) isn't currently supported.


You can test various aspects of your page.


**•**


Test the variant that you're currently working on, including modals,
viewports, and dynamic data by selecting the **Preview** button, which
opens an overlay.


**•**


**•**


Test with different data by changing the test values and selecting
**Apply** . For more information, see Test values in a page.


See what the variant looks like at different screen widths by selecting a
form factor icon. For example, view the variant at tablet or mobile size.
For more information about creating pages for different form factors,
see Responsive authoring.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-268-1.png)


**Note:** If you edit the test values or the form factor when previewing,
the new test values or form factor are retained when you view the
page variant in the editor. For example, if you changed the form
factor to mobile while previewing, the page variant is displayed in
the editor at the mobile form factor. You can always change to
another size by selecting a form factor icon.


When you have finished testing, select the **X** in the upper right to close
the overlay.


**Test your page as an end user**


Test which variant users see by opening the URL path. Select the arrow
next to the **Preview** button and in the drop-down list select **Open URL**
**path** . UI Builder checks the audience, conditions, and condition order,
and then opens the appropriate variant in a new browser tab. When you
have finished testing, close the tab.

## Organize components in UI Builder pages


Column layouts organize components on a UI Builder page. Learn how
column layouts are used in UI Builder.


Column layouts enable you to create useful and visually appealing
pages in an experience. A column layout is a type of flexible container


that can hold components. Column layouts can have columns of equal
or different widths. You can configure the column layout as a whole
and the individual columns within the layout. For example, set a different
border width and color for a column layout and for the individual
columns within the layout. Column layouts can contain empty columns
on a UI Builder page to create white space. Use multiple column layouts
on a page. For example, a two-column layout could contain a header
and image, then a three-column layout below it could hold more
components like a list and form.


Think about the layout of your page before you begin building it. Analyze
what you want to achieve and how complex the page layout must be.
These questions determine what type of column layout or layouts you
should use.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-269-1.png)


Column layouts in UI Builder use standards-based Cascading Style Sheets
(CSS) rules and web layout technologies such as Flexbox, CSS grid, and
absolute positioning. So whatever you can do in CSS you can do here.
[Visit Mozilla to learn more about CSS.](https://developer.mozilla.org/en-US/docs/Web/CSS)


**Note:** If you have existing UI Builder pages created in an
earlier release (Utah or Tokyo), you can upgrade to Vancouver or
Washington DC and add column layouts to the pages.


**•** Column layouts


Column layouts are used to design and organize UI Builder pages.


**•** Upgrading layouts in UI Builder


Upgrade layouts created in Quebec and Rome to the new layout
system.


**•** Using Flexbox layouts in UI Builder


Create a Flexbox layout in UI Builder to build powerful pages so that you
can customize with cascading style sheets (CSS) and can improve your
performance.


**•** Using CSS Grid layouts to build a page


Create a CSS Grid layout in UI Builder to build powerful pages so that
you can customize with cascading style sheets (CSS) and can improve
your performance.


**•** Change the layout of a page created in Quebec or Rome


Add and modify your layout design to change the way your page
looks. Choose how components are displayed on a page through
Cascading Style Sheets (CSS) web layout technologies, such as Flexbox
and CSS Grid.

## **Column layouts**


Column layouts are used to design and organize UI Builder pages.


This video shows you how to perform the following procedure.


Column layouts enable you to create useful and visually appealing
pages in an experience. A column layout is a type of flexible container
that can hold components. Column layouts are simple layouts that are
preconfigured, enabling you to design an efficient and attractive page
quickly. It's useful to define and set the structure of the page with column
layouts before adding components.


Column layouts can have columns of equal or different widths.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-272-1.png)


You can configure the column layout as a whole and the individual
columns within the layout. For example, set a different border width and
color for a column layout and for the individual columns within the layout.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-272-2.png)


**Note:** Currently, hiding/showing columns in a column layout based
on conditions isn't supported.


**Add a column layout**


Add a column layout in UI Builder to build structure and organize
components on an experience page.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder or open a page.


4. Select **+ Add content** in the content tree.


5. Select one of the **Basic** options on the **Layouts** tab.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-273-1.png)


The column layout appears on the stage so
you can add components to the columns. See


Add and configure components for more information.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-274-1.png)


6. Add additional column layouts above or below.


**•** In the content tree, select and hold (or right-click) on a column
layout name or select the Menu icon for a column layout. Then,
select **Add before** or **Add after** from the list and select a layout.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-274-2.png)


**•** On the stage, select a column layout, and then select the plus
sign at the top or bottom.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-275-1.png)


**Configure column layouts**


Configure column layouts in UI Builder to add the appropriate number of
columns and the look you want on an experience page.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder or open a page.


4. If the page doesn't already contain a column layout, Add a column
layout.


5. Add (up to a maximum of six) columns using the content tree, the
stage, or the configuration panel.


**•** In the content tree, select and hold (or right-click) on a column
name or select the Menu icon for a column and then select **Add**

**column before** or **Add column after** from the list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-276-1.png)


**•** On the stage, select a single column, select the Menu icon next
to the column name, and then select **Add column before** or **Add**
**column after** from the list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-277-1.png)


**•** On the stage, select and hold (or right-click) on a column and
then select **Add column before** or **Add column after** from the list.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-277-2.png)


**•** In the content tree, select a column layout and then on the
stage select the + plus icon to add columns to the right side of
the column layout.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-278-1.png)


**•** In the content tree, select a column layout and then in the
configuration panel use the + plus icon next to **Columns** to add
columns to the right side of the column layout.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-278-2.png)


**Note:** Columns can be nested inside one another, but this level
of complexity isn't often required on pages.


6. Rename a column by editing the column label from the content tree,
the stage, or the configuration panel.


**•** In the content tree, select and hold (or right-click) on a column
name or select the Menu icon for a column, select **Rename** .


**•** On the stage, select the Menu icon next to a column name,
select **Rename** .


**•** In the configuration panel, select the information icon next to the
column name.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-279-1.png)


Renaming columns can help you distinguish between different
columns on the stage and in the content tree. If you have a complex
page with many column layouts and columns, it is useful to rename
columns.


7. To change the width of a column in a layout, select the column
layout (in the content tree or on the stage), then drag a column
divider on the stage left or right to make the column narrower or
wider.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-279-2.png)


The width percentages at the top of the columns change
automatically as you drag the column divider. The percentages
add up to 100%. When resizing a column, be aware of how much
space the component or components within the column need.
For example, list and form components usually don't display well in
narrow columns.


8. Distribute columns in a layout evenly across the horizontal using the
content tree, the stage, or the configuration panel.


**•** In the content tree, select and hold (or right-click) on a column
layout name or select the Menu icon for a column layout, and
then select **Distribute columns evenly** from the list.


**•** On the stage, select a column layout, select the Menu icon next
to the column layout name, and then select **Distribute columns**
**evenly** from the list.


**•** Select a column layout (in the content tree or on the stage) and
in the configuration panel select **Distribute columns evenly** .


9. Reorder columns (including their contents) within a column layout
using the content tree or the stage.


**•** In the content tree, select the column and drag it to a different
position (a blue horizontal line shows where the column can be
dropped).

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-280-1.png)


**•** On the stage, select a column header, drag the column to
a different position, and drop the column into the drop zone
defined by a vertical magenta line.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-281-1.png)


If you reorder the column in the content tree the stage updates, and
if you reorder on the stage the content tree updates.


10. Specify the amount of space between columns from the content
tree, the stage, or the configuration panel.


**•** In the content tree, select and hold (or right-click) on a column
layout name or select the Menu icon for a column layout, select
**Layout** from the list, and select a size option in **Column gap** .


**•** On the stage, select a column layout, select the Menu icon next
to the column layout name, select **Layout** from the list, and select
a size option in **Column gap** .


**•** Select a column layout (in the content tree or on the stage) and
in the configuration panel select a size option in **Column gap** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-282-1.png)


11. Select the Tree icon to navigate to a different layer of content, for
example, from a column to the parent column layout or a child
component.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-282-2.png)


12. Delete columns from the content tree or the stage.


**•** In the content tree, select and hold (or right-click) on a column
name or select the Menu icon for a column, and then select
**Delete column** from the list.


**•** On the stage, select a single column, select the Menu icon next
to the column name, and then select **Delete column** from the list.


**•** In the content tree, select a column layout and then in the
configuration panel use the - minus icon next to **Columns** to
remove columns from the right side of the column layout.


For information about editing column spacing, see Set the gap
between components in columns.


**Set the gap between components in columns**


In UI Builder, if a column contains multiple components, set the gap
between the components.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder or open a page.


4. If the page doesn't already contain a column layout, Add a column
layout.


5. Within a single column, add two components


a. In the content tree, identify a column and select **+ Add content**
under the column name.


b. In the toolbox window, select a component, for example, **Avatar** .


c. In the content tree, move your mouse over the name of the
component you just added, select the open menu (three vertical
dots) icon, and select **Add after** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-284-1.png)


d. In the toolbox window, select another component, for example,
**Button** .


6. Select **Save** .


7. In the content tree, select the column to which you added the two
components.


8. In the configuration panel, select a size option in **Gap** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-285-1.png)


9. To specify an exact gap size in pixels, move your mouse over the
**Gap** field, select the **Use custom value** (pencil) icon, and type in a
number, for example, `300px` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-285-2.png)


10. To change between stacking the components and placing them
next to each other in the column, select the **Row** or **Column** icon in
**Direction** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-286-1.png)


To reverse the order and placement of the components in the
column, select the **Advanced** (three horizontal dots) icon in **Direction**,
and then select the **Reverse** option.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-286-2.png)


**Set advanced column layout options**


Set advanced column layout options in UI Builder including stack width
and column layout height.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder or open a page.


4. If the page doesn't already contain a column layout, Add a column
layout.


5. Select a column layout containing two or more columns in the
content tree.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-287-1.png)


6. To set a stack width, go to **Configuration panel > Layout** and select
**Show advanced layout options** .


**Note:** Setting a stack width enables you to control how a page
with column layouts looks in a narrow browser window, tablet, or
mobile device.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-287-2.png)


7. Type a width in **Stack columns below** .


8. Select **Save** .


9. To test the updated stack width, select the arrow next to **Preview** and
select **Open URL path** .


10. Reduce the browser window width to less than the stack width that
you specified to check that the columns on the right move below the
first column.


11. Close the browser tab that opened with the URL path.


12. To control column layout height, select a column layout with two
or more columns in the content tree, go to **Configuration panel >**
**Layout**, and select **Show advanced layout options** .


**Note:** Setting height is useful if your column layout contains a
component that can be tall, like the List component.


13. Under **Sizing**, type numbers into one or more of the options ( **Height**,
**Min. H**, and **Max. H** ), and set the sizing unit (for example, **px**, **%**, or
**em** ).

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-288-1.png)


14. Select **Save** .


15. To test the updated sizing, select the arrow next to **Preview** and
select **Open URL path** .


16. Reduce and expand the browser window height to test the specified
values.


17. Close the browser tab that opened with the URL path.


## **Upgrading layouts in UI Builder**


Upgrade layouts created in Quebec and Rome to the new layout
system.


The UI Builder layout system was enhanced and updated in the San
Diego release. This new layout system features a simplified content tree
and a new styling panel for layout configuration and component styling.
All newly created page variants use the new layout system. You have
the option to upgrade to the new layout system for existing and custom

pages.


The new layout system includes the following:


**•** A simplified content tree


**•** Improved styling panel for layout configuration and component styling


**•** [Low-code UI for configuring CSS Flexbox and Grid layouts.](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)


**•** Enhanced UI for component styling


**•** Updated layouts do not require slots


**Things to look for after upgrading layouts**


Variants and pages are upgraded individually.


A page/variant is made up of a layout, components, and
subcomponents, that are wrapped in a container within a layout with
data resources, event bindings, and composition. Only the layout of your
page is upgraded when upgrading to the new layout system, so there is
no impact to your data, components, or component styling.


All slots in the old layout system are migrated during the upgrade process
to the new layout. The upgrade process changes how the component
containers are structured on your page.


While component styling is not impacted, there may not be a one-to-one
style migration of how components were positioned. Complex pages
can have visual misalignments that occur through the upgrade process
as styles are merged from slots to containers. Some issues must be
resolved manually.


**Upgrade your layout to the new layout system**


Upgrade your UI Builder pages to the new layout system.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience with the page you want to upgrade.
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select the page that you want to upgrade.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-290-1.png)


You can find page variants that can be upgraded to the new layout
system tagged with a red dot.


**Note:** Legacy pages created using the pre-Quebec row/
column layout system are not upgradable and must be rebuilt
with the new layout system.


4. Select the **Update layout** button.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-291-1.png)


UI Builder begins updating your page layout to the new layout
system. A notification appears when the process is complete.


5. You can compare your old layout to the upgraded layout by
selecting **compare the two layout versions** in the **Layout needs review**
**before you can edit** notification.


Two browser tabs open, one displaying your current layout and one
displaying the upgraded layout.


6. Select **Keep new** if you would like to update the page to the new
layout system, or select **Use old** if you would like to keep the page
layout as it was.
A modal appears asking you to confirm your selection.


7. Select **Keep new** to complete the upgrade to the new layout system,
or select **Use old** to reverse the upgrade process and return the page
to the old layout system.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-292-1.png)


8. The page reloads with the changes applied.


9. View and test your page by selecting the **Preview** button


( ).

## **Using Flexbox layouts in UI Builder**


Create a Flexbox layout in UI Builder to build powerful pages so that you
can customize with cascading style sheets (CSS) and can improve your
performance.


You can easily build custom pages with Flexbox layouts in UI Builder.
Customizing the layout of your page lets you take full advantage of
Flexbox so that you can achieve your overall page design. For more
information, see Organize components in UI Builder pages.


Flexbox is a one-dimensional layout system in CSS. Flexbox is inherently
flexible, which is useful for when you don’t know the size of your content.
If you plan to build complex pages, you can customize the layout of your
[page in the configuration panel styles tab or with CSS. Visit Mozilla to](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
learn more about Flexbox.


You can change the direction of your content in the layout in the
following ways:


**•** Row: Rows are organized left-to-right or right-to-left, depending on the
direction of your browser's default language. Left/right is the case for an
English browser.


**•** Row-reverse: Rows are organized in the reverse direction of your
browser's default language, such as right-to-left or left-to-right.


**•** Column: Up/down or down/up


**•** Column-reverse: Down/up
Flexbox row and column directions

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-293-1.png)


**•** Justify content: Defines the alignment along the main axis. Choices are
as follows:


**•** Flex-start: Items are at the start of the flex direction, similar to leftjustified content. This is the default setting.


**•** Flex-end: Items are at the end of the flex direction, similar to rightjustified content.


**•** Space-between: Items are distributed evenly.


**•** Space-around: Items are distributed evenly with equal space around
them.


**•** Space-evenly: The spacing between items is equal.


**•** Align items: Defines how you want your flex content displayed along
the cross axis. Choices are as follows:


**•** Stretch: Stretch your content to fill the container. This is the default
setting


**•** Flex-start: Place your content at the start of the cross axis.


**•** Flex-end: Place your content at the end of the cross axis.


**•** Center: Center your content in the cross axis.


**•** Base system: Align your content the same as your baseline alignment.


**•** Height: Set the height automatically or manually.


**•** Width: Set the height of your flexbox items automatically or manually.


**•** Margin: Set your minimal distance between flexbox items.


**•** Padding: Set the padding for each side of your flexbox items.


**Create a Flexbox layout with the new layout system**


Create a Flexbox layout in UI Builder to build powerful pages in a lowcode environment.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder.


4. Select the **+ Add content** button in the UI Builder stage.


5. Select **Flexbox** in the layouts tab.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-295-1.png)


6. Select **Add** .


7. Select the **Styles** tab in the configuration panel.


8. In the **Layout** section, you should see **Flexbox** highlighted.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-296-1.png)


9. In the **Layout** section of the styles tab, you can change the following:


**Direction**


Define how you want components to stack, horizontally or vertically.


**Align Items**


Define how components within containers align as a group.


**Justify content**


Define how to pack or space apart the components within the
container.


**Note:** Select **Show advanced layout options** to see the next two
options.


**Gap**


Set the size of the gap between rows and columns.


**Wrap child elements to multiple lines**


Set whether components are forced onto one line or overflow onto
multiple lines.


[Visit Mozilla to learn more about Flexbox layout configurations.](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)


10. (Optional) You can edit the CSS code by selecting **Show advanced**
**configuration options** at the bottom of the **Styles** tab, and then
selecting the **View and edit CSS** option.


11. Select **Save** .
Your page refreshes and displays the changes made to the layout.


12. Add components to your page.
See Add and configure components for more information.


13. View and test your page by selecting .


**Create a Flexbox layout with the old layout system**


Create a Flexbox layout in UI Builder to build powerful pages so that you
can customize with cascading style sheets (CSS) and can improve your
performance.


**Before you begin**


Role required: admin


**About this task**


In the following procedure, you learn how to use Flexbox to change the
CSS code to customize the layout of your page.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder or open a page.


4. Click the **Layout** tab and choose the two-column layout.
Standard two-column-layout

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-298-1.png)


5. Click **Edit layout code** .


Edit the layout code

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-299-1.png)


6. Expand the code editor so that you can easily view the CSS code.
Expand the code editor

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-299-2.png)


7. Add another slot to the layout by copying the CSS code for an
existing slot.


Copying the code is easier than typing it into the layout.


Copy the CSS code for a slot

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-300-1.png)


8. Below the code that you copied, place a comma and then paste
the following CSS code:


a. Change the "slotName" property to `"Column 3",` .


b. Change the "flex" property to `"2"` .


c. Add `"margin-left": "1rem"` .


Paste the CSS code

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-301-1.png)


Changing the "flex" property increases the size of the column. By
using "margin-left", you add space between the previous columns.


9. Collapse the expanded view, and then click **Apply** .


Apply a layout change

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-302-1.png)


**Result**


The new Flexbox layout that you created shows the new slot that you
added to the original two-column layout.


New custom layout

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-303-1.png)


Click **Reset to original** to reset layout changes back to the original.
Reset a layout

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-303-2.png)


Related tasks


**•** Create a CSS Grid layout with the old layout system


## **Using CSS Grid layouts to build a page**


Create a CSS Grid layout in UI Builder to build powerful pages so that you
can customize with cascading style sheets (CSS) and can improve your
performance.


CSS Grid is the most powerful layout system in CSS. CSS Grid is built on
top of a two-dimensional grid. CSS Grid gives you control over how you
create your pages. Use UI Builder to implement a CSS Grid layout using
low-code layout configuration properties. For advanced layouts, you can
[view and edit CSS code to customize your layouts. Visit Mozilla to learn](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)
more about CSS Grid.


For example, you can have a grid with three columns and three rows to
make a grid nine cells. You can place components inside these cells or
make the component span multiple cells.


CSS Grid layout

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-304-1.png)


Customizing the layout of your page lets you take full advantage of
CSS Grid so that you can achieve your overall page design. For more
information, see Organize components in UI Builder pages.


To find out more about CSS layouts within your UI Builder instance, you
can find them in the [sys_uib_template] table.


**Create a CSS Grid layout with the new layout system**


Create a CSS Grid layout in UI Builder to build powerful pages in a lowcode environment.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder.


4. Select the **+ Add content** button in the UI Builder stage.


5. Select **Grid** in the layouts tab.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-306-1.png)


6. Select the **Styles** tab in the configuration panel.


7. In the **Layout** section, you should see **Grid** highlighted.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-307-1.png)


8. In the **Layout** section of the styles tab, you can change the following:


**Columns**


Defines the number, order, and width of grid columns.


**Rows**


Defines the number, order, and width of grid rows.


**Direction**


Sets whether newly added components are stacked horizontally or
vertically.


**Gap**


Sets the size of the gap between rows and columns.


**Note:** Select **Show advanced layout options** to see the next four
options.


**Align items**


Defines how components within the container align as a group.


**Justify items**


Defines how the browser distributes space between and around
content items along the inline axis of a grid container.


**Align content**


Sets the distribution of space between and around content items
along a grid's block axis.


**Justify content**


Defines how to pack or space apart the components within the
container.


[Visit Mozilla to learn more about CSS Grid layout configurations.](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)


9. (Optional) You can edit the CSS code by selecting **Show advanced**
**configuration options** at the bottom of the **Styles** tab, and then
selecting the **View and edit CSS** option.


10. Select **Save** .
Your page refreshes and displays the changes made to the layout.


11. Add components to your page.
See Add and configure components for more information.


12. View and test your page by selecting .


**Create a CSS Grid layout with the old layout system**


Create a CSS Grid layout in UI Builder to build powerful pages so that you
can customize with cascading style sheets (CSS) and can improve your
performance.


**Before you begin**


Role required: admin


**About this task**


In the following procedure, you learn how to use CSS Grid to modify your
CSS to customize the layout of your page.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder or open a page.


4. Click the **Layout** tab and choose the two-row by two-column layout.


Standard two-row, two-column layout

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-310-1.png)


5. Click **Edit layout code** .
Edit the layout code

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-310-2.png)


6. Expand the code editor so that you can easily view the CSS code.


Expand the code editor

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-311-1.png)


7. Add another slot to the layout by copying the CSS code for an
existing slot.


Copying the CSS code is easier than typing it into the layout.


Copy the CSS code for a slot

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-312-1.png)


8. Paste the CSS code below the code that you copied and change
the slotName and grid-area to a unique value.


Paste the CSS code

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-313-1.png)


9. Modify the layout rules to include the new column and template
area, as follows:


a. Delete the `"Grid-template-columns": "1fr 1fr",` line.


b. Add a second `cell1` after `cell1`, and then add `cell5` after

`cell4` .

Modify the layout rules

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-313-2.png)


You can set many different configurations. In this example, there
are the two resulting grids from two different grid template areas.


The "grid-template-areas" property being modified is setting the CSS
[property of the same name. For more information, see MDN grid-](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)
[templates-areas.](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)


Grid template areas

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-314-1.png)


10. Collapse the expanded view, and then click **Apply** .


Apply a layout change

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-315-1.png)


**Result**


The new CSS Grid layout shows that the new slot was added to the
original two-row, two-column layout.


New custom layout

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-316-1.png)


Click **Reset to original** to reset the layout changes back to the original at
any time.
Reset a layout

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-316-2.png)


Related tasks


**•** Create a Flexbox layout with the old layout system


## **Change the layout of a page created in Quebec or** **Rome**


Add and modify your layout design to change the way your page looks.
Choose how components are displayed on a page through Cascading
Style Sheets (CSS) web layout technologies, such as Flexbox and CSS
Grid.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Layouts control what containers and components are available on a
page, and where they are. CSS rules apply to them. You can change the
layout as follows.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. Select the **Layout** tab.


5. Depending on the type of page, do one of the following to select a
container to update.

|Type of page|Instruction|
|---|---|
|Existing page|Select the container on your<br>page for which you want to<br>change the layout.|


|Type of page|Instruction|
|---|---|
||**Note:** Alternately, you<br>can select the container<br>in the content tree to the<br>left of the main page area.<br>When the page structure<br>is in the structured tree,<br>you can more easily find<br>the container you want<br>to change. If you have<br>many components and<br>containers in the content<br>tree, use the search bar to<br>find a specific container.|
|New page<br>|In the content tree to the left of<br>the main page area, select the<br>**Body** of your page.<br>**Body** is the root element of the<br>page.<br>|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-318-1.png)


If you are starting a new page, you can select the layout at the page
level, and later at the container level. If you are not the owner of an
existing page, be aware of the impact of changing the layout at the
page level.


6. Change the layout of your container.


a. In the Page configuration pane, select the **Layout** tab to select
the layout that you want to use.


You can change the current layout of an existing page into a
new one. For example, in a three-column layout, you can click
the four-column layout to change the layout.


You can also set the layout for a container. The following image
shows the layout options for the UI Builder.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-319-1.png)


b. If you are creating a page, add components to the new areas in
your layout.


c. Click **Save** .


d. View and test your page by selecting .
For changing an existing page, the following video shows how you
can change the container layout from three to four columns, and
then add a new component to the fourth column.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-320-1.png)


For setting the layout of a new page, the following video shows you
how to set the layout that you want for the page. For example, you
can set your page to have two slots or columns. Then, you can add
containers to each slot and change the layout for each container.
You can also set the layout at the container level after you add
containers to your page.


Change the layout of a page

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-321-1.png)


7. Add components to slots.
You build your page with containers components. See Customize UI
Builder pages using components for more information.


You can add components by using any of the following ways.

|To add a component|Do the following|
|---|---|
|Directly from your page (option<br>1)|Select the add content (plus)<br>icon, select the**Components**<br>tab, and then select a<br>component.|


|To add a component|Do the following|
|---|---|
|||
|Directly from your page (option<br>2)|On a column layout or<br>component, select the add<br>before (plus) or add after<br>(plus) icon, and then select a<br>component.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-322-1.png)


|To add a component|Do the following|
|---|---|
|||
|From the content tree|In the content tree, select**+**<br>**Add content** and then select a<br>component.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-323-1.png)


|To add a component|Do the following|
|---|---|
|||
|From the floating menu above<br>the page|On a column layout or<br>component, select the Menu<br>icon, select**Add before** or<br>**Add after**, and then select a<br>component.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-324-1.png)


|To add a component|Do the following|
|---|---|
|||


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-325-1.png)


8. Modify the layout styling options in any of the following ways.

|Option|Instruction|
|---|---|
|Change the<br>layout styling|a. Click a container for which you want to<br>change the layout.<br>You can click the container in the content<br>tree, or you can click the container on the<br>page.<br>b. From the floating menu above the page,<br>click**Layout**.<br>c. Choose to display your content as either<br>Flex or Grid. For more information about flex<br>or grid options, seeUsing Flexbox layouts in|


|Option|Instruction|
|---|---|
||UI Builder orUsing CSS Grid layouts to build<br>a page.|
|Choose Flex|a. From the Display list, select**Flex**.<br>b. Select the following options based on how<br>you want to display your container content<br>on the page. The options can also be<br>entered in the CSS styles box:<br>**•** Flex direction: Choose from**Row**, **Row-**<br>**reverse**, **Column**, or**Column-reverse**.<br>**•** Justify content: Choose from any of the<br>following:<br>**• Flex-start**: Items are at the start<br>of the flex direction, similar to left-<br>justified content. This is the default<br>setting.<br>**• Flex-end**: Items are at the end of<br>the flex direction, similar to right-<br>justified content.<br>**• Space-between**: Items are<br>distributed evenly.<br>**• Space-around**: Items are<br>distributed evenly with equal space<br>around them.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-326-1.png)


|Option|Instruction|
|---|---|
||**• Space-evenly**: The spacing<br>between items is equal.<br>**•** Align items: Defines how you want your<br>flex content displayed along the cross<br>axis. Choices are as follows:<br>**• Stretch**: Stretch your content to fill<br>the container. This is the default<br>setting.<br>**• Flex-start**: Place your content at<br>the start of the cross axis.<br>**• Flex-end**: Place your content at the<br>end of the cross axis.<br>**• Center**: Center your content in the<br>cross axis.<br>**• Baseline**: Align your content the<br>same as your baseline alignment.<br>**•** Height: Set the height automatically, or<br>manually.<br>**•** Width: Set the height of your flexbox<br>items automatically or manually.<br>**•** Margin: Set your minimal distance<br>between flexbox items.<br>**•** Padding: Set the padding for each side<br>of your flexbox items.|


|Option|Instruction|
|---|---|
|||
|Select Grid|a. From the Display list, select**Grid**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-328-1.png)


|Option|Instruction|
|---|---|
||b. Fill in the following information:<br>**•** Height: Set the height automatically, or<br>manually.<br>**•** Width: Set the height of your grid items<br>automatically or manually.<br>**•** Margin: Set your minimal distance<br>between grid items.<br>**•** Padding: Set the padding for each side<br>of your grid items.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-329-1.png)

## Customize UI Builder pages using components


Learn what a component is in UI Builder. Also, see how components work
within UI Builder.


Components are the base elements of your UI Builder page. Components
range from core elements like buttons and labels to more complex
experience components like lists and forms.


You can add these components to your UI Builder page to build or
customize your workspace or portal experience. For example, adding an
**Activity stream** component to your page that lets users see their travel
request activity.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-330-1.png)


You can add components to your UI Builder page in the following ways.


**Ways to add a component to a page**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-330-2.png)


|Location|Example|
|---|---|
|||
|Directly from a page in UI Builder<br>(option 2)|On a column layout or<br>component, select the add before<br>(plus) or add after (plus) icon, and<br>then select a component.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-331-1.png)


|Location|Example|
|---|---|
|||
|From the**Content** tree in UI Builder|In the content tree, select**+**<br>**Add content** and then select a<br>component.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-332-1.png)


|Location|Example|
|---|---|
|||
|From the floating menu above the<br>page in UI Builder|On a column layout or<br>component, select the Menu icon,<br>select**Add before** or**Add after**,<br>and then select a component.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-333-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-334-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-334-1.png)

**Column layouts in UI Builder**


Add column layouts and columns to your UI Builder page first. Then add
components to the columns in a column layout to build and customize
your page. Think of a column layout as a defined part of the screen
where you add components like lists and headings. You can have as
many column layouts on a UI Builder page as you want, with as many as
six columns in any column layout. Multiple components can be added to
a single column. View the structure of your page in the **Content** tree.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-335-1.png)


For more information, see Column layouts.


**Configure components in UI Builder**


There are three ways to configure a component in the configuration
panel.


**•** Configure the component properties.


**•** Add CSS style overrides.


**•** Set up event handlers for the components.


**Configure tab**


Component properties vary based on each component. Component
configuration can be simple, as is the case with simple elements
like buttons, headings, and labels. Components like lists and forms
require significant configuration. For icon and image components, select
from a variety of options or use a custom icon or image. You can
modify component properties with UI Builder's low-code JSON editor. For


[more information about configuring components, see Next Experience](https://developer.servicenow.com/dev.do#!/reference/next-experience/components?&query=&order_by=nameAsc&limit=120&offset=0&categories[]=uib_component&categories[]=uib_macroponent-component&categories[]=uib_facades)
[Components.](https://developer.servicenow.com/dev.do#!/reference/next-experience/components?&query=&order_by=nameAsc&limit=120&offset=0&categories[]=uib_component&categories[]=uib_macroponent-component&categories[]=uib_facades)


For each property in the component configure tab, you can choose from
the following options.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-336-1.png)


**•** Static: Use data from a list, or enter your own data. The data doesn't
connect to an external data source.


**•** Dynamic data binding: A way to bind a component property to a data
resource, page property, or client state.


**•** Script: Enter JavaScript code to populate a property value.


**Styles tab**


You can change the Cascading Style Sheets (CSS) styles for individual
components. Change color borders, font size, and so on.


**Events tab**


Configure page-level and variant-level event mappings. Also add
dispatched events and handled events for your variant. The more
complex, experience components rely heavily on dynamic data that is
provided by a data resource. Binding dynamic data to a component is
an important feature. You dynamically expose data from tables, records,


or other elements on your page. Exposing data enables you to reuse your
components. Also, you can point to the configuration fields to see icons
data or scripting options for each field.


As you add and configure components on the page, the stage shows
your work. If you make changes and the updates do not load on the
stage, select the **Open menu** icon and then select **Developer > Reload**
**Stage** . Reloading the stage shows your changes, but does not save them.
To save your work, select **Save** at the top right.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-337-1.png)


**Component Presets in UI Builder**


Use component presets to automatically configure components on
compatible pages. UI Builder page templates contain controllers that
presets use to define component configuration values. For more
information, see Automatically configure components using presets.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-338-1.png)


**Component properties sections**


Component properties are grouped into sections of similar properties.
Open and close sections by selecting the arrows to the right of the
property headings. UI Builder admins can select which component
configuration properties are displayed or hidden based on UI policies.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-339-1.png)


**Component formula editor**


Use the UI Builder component formula editor in the configuration
panel to bind or modify formulas. You can enter text, data bindings,
and/or formulas. Formulas can consist of any combination of the three
input types. The component formula editor supports logical, arithmetic,
comparison, negation, and functional transform types.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-340-1.png)


Each function added to the component formula editor auto-completes.
The component formula editor displays a label for each input of the
function so you know what parameters each function requires. For more
information about the supported functions in the component formula
editor, see Supported functions in the UI Builder component formula
editor.


**Component ID**


Use the component ID when you add a script or bind data to the
component as a way to reference the component. A component ID
is automatically created and is based on the component label when
you add a component to a page. You can change the component ID
to anything you want, as long as it is unique. Select the name of the
component in the configuration panel to see the component ID.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-341-1.png)


**Component visibility**


Select the eye icon in the configuration panel to set component visibility.
Component visibility is based on a property of the component itself,
not who is viewing it. You could show or hide a component based on
conditions. For example, hiding an image if it has a broken link.


You can set the visibility based on dynamic data binding, or by editing a
scripted property value.


Set the **Test value** to test what happens when the visibility is set to true,
false, or none.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-341-2.png)


**Duplicate components**


Create an exact copy of a configured component on your UI Builder
page except for the name and ID. A duplicated component copies all
properties, bindings, and events. For more information, see Duplicate a
component.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-342-1.png)


**•** Automatically configure components using presets


Use component presets to automatically configure components on
compatible pages.


**•** Create custom presets for components


Create presets to save time and make your component configurations
reusable across different experiences.


**•** Change the default appearance of components


Set the styles for components and wrappers to change the default

appearance.


**•** Enhance accessibility with focus management


Set focus on specific elements, ensuring users can interact with them
effectively using screen readers.


**•** Duplicate a component


Duplicate a configured component to reuse on a page.


**•** Dynamically display content with conditional renderers


Use the conditional renderer component to display content or
components based on specified conditions.


**•** Page collections


Page Collections are groups of pages that can be used across multiple
experiences.


**•** Change data visualizations in UI Builder


Change data visualizations in real time using a drop-down list to
preview data in your experience.


**•** Add tabbed content to UI Builder pages


Use the Tabs component to add tabbed content to pages in UI Builder.


**•** Add a contextual sidebar


Add a contextual sidebar to a page with UI Builder to display related
content using a vertical tab structure.


**•** Add forms to UI Builder pages


Use the Form component to add one or more forms to UI Builder pages.


**•** Create modals in UI Builder


Use modals in UI Builder with components to provide alerts or calls to
action for a user. UI Builder comes with modals to save time and effort.


**•** Extend your UI experience with viewport components


Viewports are specialized components that enable you to extend your
experience without needing to own the parent page in UI Builder.
You can work with viewports in three ways. You can add a viewport
component or a viewport-enabled tab to a page, or add a viewport to
the Contextual sidebar component.


**•** Create popovers in UI Builder


Use popovers on a UI Builder page to overlay contextual information or
functionality to help users complete tasks.


**•** Create modeless dialogs in UI Builder


Use modeless dialogs on a UI Builder page to add a floating window
that enables you to interact with both the window content and the
page content below.


**•** Configure alerts to auto-dismiss


Set alerts to automatically clear after a specified time period.

## **Automatically configure components using presets**


Use component presets to automatically configure components on
compatible pages.


Use component presets to apply predefined configuration values and
event mappings to components. UI Builder page templates contain
controllers that presets use to define component configuration values.


Presets apply pre-built configurations to component properties and event
handlers and are only available for certain components. They are based
on common use cases for components, such as configuring a **Form**
component with fields that are typically included on a record page.


Applying a preset automatically configures components to work
immediately, simplifying page creation and maintenance for page
authors.


Presets offer the following benefits to page authors:


**•** Handling of complex data and event binding for components


**•** Reduced cost of ownership and maintenance due to being defined
external to pages


From the Configuration pane, you can select whether to apply a preset
to the selected component or instead manually configure it. Default
presets are automatically applied for components when a page is
created from a template or the controller required for the preset is
already added to the page. Any properties or events configured by the
preset display as read-only when a preset is applied.


You can override values configured by a preset but in doing so you
assume ownership of the component configuration and maintenance.


Sub-pages do not inherit controllers and are not able to use presets in
Zurich.


Preset applied to a component

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-346-1.png)


**Data and event bindings**


Presets can include bindings to:


**•** Controller output properties (@data)


**•** Event payloads (@payload)


**•** Session context (@context.session)


**•** Complex formulas (client transforms)


Presets can also include event mappings to a controller's handled events.
For more information, see Manage actions in UI Builder pages.


**Controllers**


Presets connect components to data and event mappings using a
controller. If the controller required by a preset is not already on the
page, the preset prompts you to configure the controller's required
properties and adds the controller. After a controller is added to a page,
components that have presets associated with the controller appear
highlighted in the components list. For more information, see Bind data
to UI Builder pages using controllers (advanced feature).


Components with presets

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-348-1.png)


Check the **Presets available** box to view components with presets in the
toolbox.


**Select a component preset**


Choose a component preset when adding a component to your page.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Open the toolbox.


5. Select the **Presets available** box.


6. Select the component you want to add to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-350-1.png)


7. The component automatically configures with the default preset.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-351-1.png)


8. (Optional) Select a different preset from the list in the configuration
panel.
You can configure a component not to use a preset by selecting
**Remove current preset** .


a. Select a new component preset in the configuration panel.


b. Select **Apply** to replace the existing preset.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-352-1.png)


9. Click **Save** .


**Override a component preset**


Override a component preset to enter your own custom values.


**Before you begin**


Role required: admin


**Procedure**


1. Select a component with a preset.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-353-1.png)


2. Find the data value that you want to override in the configuration
panel.


3. Click the lock icon in the data field.


4. Enter the data value that you want to override the preset value.


5. Select **Save** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-354-1.png)


**Result**


The configuration panel displays the custom value in the field.


**Reset a component**


Reset component presets to their default values.


**Before you begin**


Role required: admin


**Procedure**


1. Select the component that you want to reset in the content tree.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-355-1.png)


2. Select the component name in the configuration panel.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-356-1.png)

3. Click **Reset component** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-357-1.png)


4. Click **Reset** .


**Result**


The component preset resets to the default values.

## **Create custom presets for components**


Create presets to save time and make your component configurations
reusable across different experiences.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Select **Create** .


3. Select **Preset** .


4. On the form, fill in the fields.


**Create a page collection form**


**Field** **Description**


|Name|Name to track your preset<br>internally.|
|---|---|
|Component|Select the component you want<br>to create a preset for.|
|Controller|Select the controller with data<br>and logic to power the preset.|
|Description|Short description to help find<br>your preset. Write a description<br>that helps page builders<br>understand what content is<br>included in the preset.|


5. Select **Create** .
The preset building window opens.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-359-1.png)


6. Enter controller test values to preview data in the component preset.


7. Configure the component properties you want to apply with the
preset.


8. Bind data from the controller to the component preset by dragging
items from the data preview section to the fields in the configure
panel.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-360-1.png)


9. (Optional) Add events to the component.
For more information, see Configure an event handler manually.


10. Select **Save** .


**What to do next**


Apply the preset you just created by selecting a preset in UI Builder.

## **Change the default appearance of components**


Set the styles for components and wrappers to change the default

appearance.


This video shows you how to perform the following procedure.


**Before you begin**


Role required: ui_builder_admin


**About this task**


This task describes how to add styles to components and the wrappers
(such as Body, column layouts, or a column) containing components.
Customize component styling by selecting the component in the Content
tree or apply styles to multiple components by placing components
inside a wrapper.


For information about adding styling to your entire experience, see
Manage the visual style of UI Builder experiences.


This task applies to the new layout system introduced in Zurich. If your
page is using the old layout system, see Add styling to a component
using the old layout system for more information.


**Note:** As you add and configure components on the page, the
stage shows your work. If you make changes and the updates do
not load on the stage, select the **Open menu** icon and then select
**Developer > Reload Stage** . Reloading the stage shows your changes,
but does not save them. To save your work, select **Save** at the top
right.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-362-1.png)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. In the Content panel, select a component or wrapper (for example,
Body, a column layout, or a column) for which you want to add
styling.


5. For Body or a component, select the **Styles** tab in the configuration
panel.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-363-1.png)


6. Use the visual representations on the **Styles** tab to decide what is best
for the look and feel of your page.


**Accessibility (Column layout and Column)**


Specifies accessibility settings such as ARIA Region Name,
ARIA Region Heading Level, ARIA Role, and inclusion of ARIA
Heading. For detailed information, see the ARIA documentation on
[developer.servicenow.com.](https://developer.servicenow.com/dev.do#!/reference/next-experience/utah/ui-framework/advanced/accessibility)


**Alignment (Column and Component)**


For a column, defines how components align within the column as a
group. For a component, defines how the component aligns within
the parent layout element, such as a column or column layout.


**Background (Body, Column layout, Column, and Component)**


Sets the background color behind the layout element. Select a color
from the color picker **My Colors** tab where you can view available
colors in a grid or a list. Alternatively, use the **Custom** tab to specify
any color in HEX, RGB, or HSL.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-364-1.png)


**Border (Column layout, Column, and Component)**


Adds a border around the content. The border is placed on the
immediate inside of the margin and the immediate outside of the
padding. Specify the border thickness, type, color, and corner shape.
For components, you have the option to use custom CSS for the
border.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-364-2.png)


**Layout (Body, Column layout, Column, and Component)**


For body and column, specifies direction, alignment, and content
justification. For column layout, specifies the number of columns and
the column gap (space between columns). For some components,
such as Card Base Container, select **Edit CSS** to apply specific CSS
styles to the container layer and to the internal layer controlling
components within the container.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-365-1.png)


**Shadow (Column layout, Column, and Component)**


Adds shadow effects around the content. You have the option to use
custom CSS.


**Sizing (Component)**


For applicable components, sets the default, minimum, and
maximum height and width for the component (in px, %, em, rem, or
a custom value). This value is relevant for when the browser window is
resized.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-366-1.png)


**Spacing (Body, Column layout, and Component)**


Margin sets the size of the space on the immediate inside of the
body, column layout, or component. Padding sets the size of the
space on the immediate outside of the body, column layout, or
component. Select Margin or Padding to set the same size for all four
sides.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-366-2.png)


You can set the size for each margin or padding side by selecting the
current setting and then selecting an option.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-367-1.png)


7. (Optional) For Body and components, you can edit the CSS code by
selecting the **View and edit CSS** link at the bottom of the **Styles** tab.
The **Styles tab** displays a **CSS styles** code editor. The following CSS
properties are the most commonly used:


**•** `background-color`


**•** `background-image`


**•** `border-style`


**•** `border-width`


**•** `border-color`


**•** `border-radius`


**•** `box-shadow`


**•** `height`


**•** `min-height`


**•** `max-height`


**•** `margin`


**•**
```
   overflow

```

**•** `padding`


**•** `width`


**•** `min-width`


**•** `max-width`


**•** `z-index`

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-368-1.png)


**Important:** Some components contain built-in styling
configurations that you can't override with CSS in UI Builder.
For information about overriding these style configurations, see
Manage the visual style of UI Builder experiences.


8. In the main header, select **Save** to save your changes.


**Add styling to a component using the old layout system**


Set CSS styles for a component to change its default appearance.


**Before you begin**


Role required: ui_builder_admin


**About this task**


This task describes how to add styles to the wrapper containing your
component, which is generally recommended instead of applying styles
to the component directly. Make sure that the component whose styles
that you want to define is placed within a container component to put
the component in a wrapper. Your component's wrapper is one level
higher than the component in the Content hierarchy and is labeled by
default as Main.


To add styling to an entire page, you can use standards-based CSS in the
wrapper for the page. For information about adding styling to your entire
experience, see Manage the visual style of UI Builder experiences.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


**Note:** A component must be placed in a container before
adding styles to the component.


4. Select the container holding the component you want to add styling
to.
The container is typically one level higher than the component in the
content tree.
The Styles tab appears in the configuration panel.


5. In the CSS Styles window, enter standards-based CSS properties and
values.
The following CSS properties are the most commonly used to apply
styles for components within containers:


**•** `background-color`


**•** `background-image`


**•** `border-style`


**•** `border-width`


**•** `border-color`


**•** `border-radius`


**•** `box-shadow`


**•** `height`


**•** `min-height`


**•** `max-height`


**•** `margin`


**•**
```
   overflow

```

**•** `padding`


**•** `width`


**•** `min-width`


**•** `max-width`


**•** `z-index`


**Important:** Some components contain built-in styling
configurations that you cannot override with CSS in UI Builder.
For information about overriding these style configurations, see
Manage the visual style of UI Builder experiences.


6. In the main header, select **Save** to save your changes.


Add styling to a component in the Styles configuration panel

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-371-1.png)

## **Enhance accessibility with focus management**


Set focus on specific elements, ensuring users can interact with them
effectively using screen readers.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Focus management can help users navigate experiences built with UI
Builder by directing their attention to specific elements on a page. For
example, you can point to a component when closing a modal that
updated information on a parent page.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .


See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select a component from the content tree that you want to trigger
the focus.


5. Select the **Events** tab.


6. Select **Add event mapping** .


7. Choose an event from the list.


8. Select **Continue** .


9. Specify the type of focus you want to trigger with the event.


Select **Set focus on** to direct users to a specific component on your

page.


Select **Focus parent page** to direct users to the parent page of a
modal, pop-up, or similar overlay.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-373-1.png)


10. Select **Continue** .


11. (Optional) Select the component you want to focus on from the **Set**
**focus on** list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-374-1.png)


12. Select **Add** .


13. Select **Save** .

## **Duplicate a component**


Duplicate a configured component to reuse on a page.


**Before you begin**


Role required: ui_builder_admin or admin


**About this task**


Create an exact copy of a configured component on your page except
for the name and ID. A duplicated component copies all properties,
bindings, and events. The duplicated component appears directly after
the component that is copied. If a tabs component is duplicated, all tabs
and their children are copied as well as their names and IDs are made
unique.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open the page variant with the component you want to duplicate.


4. Select the component that you want to duplicate.


5. Right-click the component.


6. Select **Duplicate** .
You can also use the keyboard shortcut **cmd + D** (Mac) or **ctrl + D**
(Windows).


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-376-1.png)


The duplicated component appears below the copied component
in the content tree.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-377-1.png)


7. Select **Save** .

## **Dynamically display content with conditional renderers**


Use the conditional renderer component to display content or
components based on specified conditions.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select **+ Add content** in the content tree.


5. Select **Components** .


6. Select **Conditional renderer** .


7. Select **+ Add condition** .


8. Choose how you want to build the condition.


|Type of condition|Description|
|---|---|
|Empty Container|Create a condition by placing<br>components in an empty<br>container.|
|Card|Create a condition by placing<br>components in a card<br>component.|
|Single component|Add a condition directly to<br>a component without using a<br>container or card. This works well<br>for showing a single component<br>only when the condition is true.|


9. (Optional) Select a component from the list if you selected **Single**
**component** in the previous step.


10. On the form, fill in the fields.


**Field** **Description**


|Component label|Label to identify the conditional<br>content.|
|---|---|
|Component ID|Unique identifier used when<br>binding data.|
|Description (Optional)|Description of the condition.|
|Render content|Select when to render the<br>content on the page.|
|Condition|Use data or formulas to set the<br>condition for rendering content.<br>The field requires a true boolean<br>value.|


11. Select **Apply** .


12. (Optional) Add components to the container or card.
For more information about adding components, see Customize UI
Builder pages using components.


13. Configure the components in the conditional renderer.


14. Select **Save** .

## **Page collections**


Page Collections are groups of pages that can be used across multiple
experiences.


**What is a page collection**


Page Collections (sys_ux_extension_point) are groups of pages that are
meant to be re-used across multiple experiences. These sets of pages
can be used in a modal viewport or in a tabs component. These pages
are sandboxed and do not have access to things like URL params or
data resources from the page that is calling them. All they have access
to is the Controller record that is specified on the Page Collection record
and that is passed down by the calling page in runtime.


Page collections are sandboxed inside of the pages they are within, this
means that they do not have direct access to change the parent page.
However, because of the way seismic works, your page collection page
can dispatch an event that the calling page can listen for to take action.
This is the only way to achieve a change in the calling page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-380-1.png)


**Why should you use page collections**


Page collections allow you to reuse custom pages across experiences.
This will save you time if you need to replicate a page for multiple
experiences and help pass information to different groups of users.


You can also use page collections to provide additional information
within an existing topic by using a viewport modal. A viewport modal will


allow your audience to view pages outside of their experience to make
changes without leaving the parent page.


Create collection of tabs that can be shared across experiences. Each
tab is an individual page in a page collection.


**Where can you use page collections**


You can access a page collection from the UI Builder home screen. The
list of page collections details which component and type each page
collection is.


You can create a page collection from the UI Builder home screen, or
from a component that uses page collections.


Page collections can be used with the following components:


**•** Viewports


**•** Viewport Modals


**•** Tabs


**Things to consider**


The page collection creation screen requires a component and
controller selection.


Data resources need to be selected to pass information to a page
collection. Need to bind data from the parent page.


Need to route to the page in a page collection you want to display in a
viewport.


Add a link to creating a page collection.


**Page collection on the platform**


You create a page collection within the ServiceNow platform. At this
time, only the Tab and Viewport component can be used when
creating a page collection. You can select a controller or pass controller
dependencies using JSON.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-382-1.png)


**•** Create a page collection across multiple UI pages


Create a page collection to accommodate tabbed content that can
be used across experiences.


Create a page collection to accommodate tabbed content that can
be used across experiences.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Use page collections to create tabbed content in your experiences with
the Tabs component in UI Builder.


Pages within a page collection don’t have access to the parent page's
URL parameters or data resources. You can set conditions for pages in a
page collection to define which page to display to certain audiences.
Page templates are not supported inside a page collection.


**Procedure**


1. Click **Create > Page collection** .


2. On the form, fill in the fields.


**Create a page collection form**


**Field** **Description**


|Name|Name to track your page<br>collection internally.|
|---|---|
|App shell UI|Type of app shell UI that<br>you want to use with the<br>page collection. The app shell<br>is the wrapper of the page<br>contents, which is similar to the<br>functionality of a web page.<br>The app shell can show things<br>like the logo of your company,<br>user preferences, and the search<br>icon. For more information, see<br>Define UI experiences using app<br>shells.|


**Field** **Description**


|Component|Select the component that will<br>use the page collection. Page<br>collections can be used with the<br>following components:<br>• Viewports<br>• Viewport Modals<br>• Tabs|
|---|---|
|Description|Short description to help<br>find your page collection.<br>Write a description that helps<br>page builders understand what<br>content is included in the page<br>collection.|


3. Click **Next** .


4. Select a controller to connect data to your page collection.
If the controller you selected depends on another controller, you will
need to add both.


5. Enter a label in the **Label** field.


6. Enter a unique Id in the **Id** field.


7. Click **Create** .


8. Click **Create new page**


9. Enter a unique name for the page in the **Name** field.


10. Specify a path for your page in the **Path** field. UI Builder generates a
default path based on the name that you provided in the previous
step.


**Note:** The application scope defaults to the scope that the
user is in. For more information about the application scope, see
Learn about security and roles.


11. Click **Continue** .


12. (Optional) Add one or more audiences for this page.
If an audience you need is not listed, you can choose the Open
audiences in platform link to create one.


13. (Optional) Add one or more conditions for this page.


14. Select the **Build responsive** option (default) for greater control of how
the page appears at different screen form factors or select **Build**
**without responsive** for automatic adjustment.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-385-1.png)


For more information, see Responsive authoring.


15. (Optional) Add more pages to your page collection.

## **Change data visualizations in UI Builder**


Change data visualizations in real time using a drop-down list to preview
data in your experience.


You can change data visualization types via a drop-down in the
configuration panel to preview different data visualization types. Each
data visualization can be configured to display different data depending
on who is using your experience. Select the drop-down under **Data**
**visualization type** to preview different types of data visualization.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-386-1.png)


A preview of the data visualization you selected appears in your page.
For information about adding data visualization components to your
experience, see Add and configure components.

## **Add tabbed content to UI Builder pages**


Use the Tabs component to add tabbed content to pages in UI Builder.


Create additional navigation on your UI Builder page by adding a Tabs
component to your page. Use the Tabs component to nest components
within tabs on your page. Tabs can be configured as either horizontal
tabs at the top of the content, or as vertical tabs on the left or right side
of the content.


Tab component example

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-387-1.png)


Tabs can be organized in the configuration panel to reorder how they
are displayed on the UI Builder page. Add custom labels and icons to
tabs to provide unique visual identifiers for navigating across tabs. These
changes can be viewed in real-time as you edit the Tabs component.


You can add one of the following types of tabs to your UI Builder page:


**•** Empty container tab


**•** Repeater tab


**•** Related list tab


**•** Page collection tabs


The tabs component supports any combination of static tabs, repeated
tabs, related list tabs, and page collection tabs. Alternatively, you can still
use the Viewport tab mode to add a series of viewports.


**Add empty container tabs**


Use an empty container tab to manually create a static set of tabs on

your page.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select the **+ Add content** button on the stage to open the toolbox.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-389-1.png)


5. Select a **Single column** layout.


6. Next, select the **+** icon in the column to open the toolbox.


7. Add a **Tabs** component to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-390-1.png)


For more information on how to add a component to a page, see
Add and configure components.


8. Select **+ Add tab** on the stage.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-391-1.png)

9. Select **Start from an empty container** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-392-1.png)


10. Select **Next** .


11. On the form, fill in the fields.


**Tab settings form**


**Field** **Description**

|Tab label|Label for the tab to display on<br>your page.|
|---|---|
|Icon|Icon to appear next to the tab<br>label. Icons are not required.|
|Hide tab|Whether to hide or display the<br>tab.|


12. Select **Create** .
The new tab displays in the **Tabs** component.


13. Select the new tab.


14. Select **+** icon.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-393-1.png)


15. Select the component that you want to add to the tab.
Components display under the tab in which they’re nested in
the content tree. For more information, see Add and configure
components.


**Result**


Your page shows the two tabs that you created. Select each tab
to further configure them, add styling, or add an event handler. For
more information on styling, see Change the default appearance of
components. For more information on adding an event handler, see
Manage actions in UI Builder pages.


**Add repeater tabs**


Use the Tabs component to create a set of repeater tabs by linking tabs
to a data array.


**Before you begin**


Role required: admin


**About this task**


You can use repeater tabs to create multiple tabs based on the data
array you provide. You can pass the icon, label, count, and fields as a
key in the object. Use the label key to add names to tabs. Use the field
key to pass information to repeater tabs. You can bind a data broker,
client state, or a client script to the data array provider to return the array
of objects with the correct schema.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select the **+ Add content** button on the stage to open the toolbox.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-395-1.png)


5. Select a **Single column** layout.


6. Next, select the **+** icon in the column to open the toolbox.


7. Add a **Tabs** component to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-396-1.png)


For more information on how to add a component to a page, see
Add and configure components.


8. Select **+ Add tab** on the stage.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-397-1.png)

9. Select **Use a repeater** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-398-1.png)


10. Select **Next** .


11. Enter a label for the repeater tab in the **Placeholder tab label** field.
This label is assigned to the first repeater tab and is the only tab
displayed in the page preview.


12. Select **Edit** in the **Data array** field.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-399-1.png)


13. Configure the data array in the JSON editor.


**Key** **Data type** **Description**


|icon|String|Name of the icon that appears<br>in UI Builder.|
|---|---|---|
|label|String|Required. Display name of the<br>tab in UI Builder.|
|count|Number|Value to provide on the tab<br>label. Dynamically bind to a<br>data broker or a client script<br>that will be displayed on the<br>label.|
|fields|Object|Object that can be used to<br>store information and to pass<br>down to the components in the<br>tabs.|


14. Select **Apply** .
The data array field displays the data array configuration.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-400-1.png)


15. Select **Create** .
The new repeater tab appears on the page and in the content tree.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-401-1.png)


16. Select **Save** .


17. Add components to the repeater tab.


18. Select to verify that the repeater tabs display correctly

on your page.


**Add related list tabs**


Create a set of tabs on a page by linking to a related list.


**Before you begin**


Role required: admin


**About this task**


The related list tab automatically populates tabs based on the record
that your page is displaying. For example, by default the related lists for
the user table are Roles, Groups, Delegates, and Visibility domains. If your
page is displaying a user record, then creating a related list tab adds
all four of these related lists as tabs on your page. You can preview
the page to see the related lists that were added. A record controller
is required to create related list tabs. To add a controller to your page,
see Bind data to UI Builder pages using controllers (advanced feature) for
more information.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select the **+ Add content** button on the stage to open the toolbox.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-403-1.png)


5. Select a **Single column** layout.


6. Next, select the **+** icon in the column to open the toolbox.


7. Add a **Tabs** component to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-404-1.png)


For more information on how to add a component to a page, see
Add and configure components.


8. Select **+ Add tab** on the stage.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-405-1.png)

9. Select **Display related lists for a record** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-406-1.png)


10. Select **Next** .


11. On the form, fill in the fields.


**Tab settings form**


**Field** **Description**

|Placeholder tab label|Placeholder label to appear on<br>the preview tab of your page.|
|---|---|
|Hide tab|Whether you want to hide or<br>display the tab.|
|Record Controller|Record controller with the<br>related list.|


12. Select **Create** .
The new related list tab displays in the **Tabs** section of the
configuration panel. Only one placeholder tab appears in the page
preview. The green icon next to the related list tab in the content tree
shows how many tabs appear on your page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-407-1.png)


13. Select **Save** .


14. View and test your page by selecting .


**Add page collection tabs**


Use page collection tabs to recreate the same tabs across multiple
pages in UI Builder.


**Before you begin**


Role required: admin


**About this task**


A page collection is a group of prebuilt globally available pages. Use
page collection tabs to render each page in a page collection as a
tab. You can select an existing page collection or can create your own.
A controller is required to add a page collection. For more information
about page collections, see Page collections.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select the **+ Add content** button on the stage to open the toolbox.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-409-1.png)


5. Select a **Single column** layout.


6. Next, select the **+** icon in the column to open the toolbox.


7. Add a **Tabs** component to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-410-1.png)


For more information on how to add a component to a page, see
Add and configure components.


8. Select **+ Add tab** on the stage.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-411-1.png)

9. Select **Add a page collection** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-412-1.png)


10. Select **Next** .


11. Select a page collection from the list or create a collection by
selecting **+ Create collection** .
To create your own page collection, see Create a page collection
across multiple UI pages.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-413-1.png)


12. Select **Add** .
The new page collection tab displays in the **Tabs** section of the
configuration panel. Only one placeholder tab displays in the page
preview.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-414-1.png)


13. Select **Save** .


14. View and test your page by selecting .

## **Add a contextual sidebar**


Add a contextual sidebar to a page with UI Builder to display related
content using a vertical tab structure.


**Before you begin**


Role required: ui_builder_admin


**About this task**


You can configure the contextual sidebar in the same way you would
configure a tab component. Each vertical tab in the contextual sidebar
renders custom content. You can place components in each tab for
quick access directly from the page.


For example, a document creation page might have the attachments
component on one tab, enabling you to attach files related to the
document that you're working on. On another tab, there could be a
nested comments component, enabling you to add and view comments
related to the document.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder. For information about creating a page
variant, see Create a page variant


4. On the stage, open the toolbox by selecting the **+ Add content**
button.


5. Select the **Single column** layout tile.


6. In the column, open the toolbox by selecting the **+** icon.


7. Select the **Contextual sidebar** component to add it to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-416-1.png)


The contextual sidebar appears on the stage, and the Tabs section
appears in the configuration panel.


8. In the configuration panel under the Tabs section, select the settings
icon ( ) to configure the tab.


a. On the form, fill in the fields.


**Tab settings form**


**Field** **Description**


|Tab label|Label that displays on the tab<br>for your page.|
|---|---|
|Icon|Icon that appears next to the<br>tab label.<br>**Note:** Icons aren't<br>required.|
|Hide tab|Option to hide or display the<br>tab.|


b. Select **Save** .


9. On the stage in the contextual sidebar, open the toolbox by
selecting the **+** icon.


10. Select the component that you want to add to the tab.
The component displays under the tab in the content tree. For more
information, see Add and configure components.


11. (Optional) To add another tab, select **+ Add** under the Tabs section.


**What to do next**


For detailed information about the configuration of the contextual
[sidebar and its properties, see Tabs UIB Setup on the ServiceNow](https://developer.servicenow.com/dev.do#!/reference/next-experience/washingtondc/now-components/now-tabs/uib-setup)
Developer Site.

## **Add forms to UI Builder pages**


Use the Form component to add one or more forms to UI Builder pages.


Add functionality to your UI Builder pages by including forms. You define
the fields on the form and their properties, such as making them required.
Then, collect data as the form is completed and submitted.


Form component example

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-418-1.png)


You can add more than one form to a single page. You can also add a
form to a page that already contains a component with a nested form.
Sample use cases include:


**•** Extend record pages by adding an inline tab with a form using its own
form controller instance.


**•** Add modals with a form on a record page.


For existing pages with forms created in a pre-Xanadu ServiceNow
release, you must apply a preset to the original form before adding
another form to the page. Applying the preset is a prerequisite to adding
multiple forms to a page and enables multiple forms to work as expected
on a page. The form controller preset should be applied onto all form
controllers.


1. Open the page containing an existing form.


2. In the data drawer, expand the **Data resources** list and select the
original form controller.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-419-1.png)


3. Select the **Preset** field.


4. Select **Form controller preset** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-419-2.png)


5. Select **Apply** .


6. Select the **X** to close the **Edit Form Controller** pop-up.


Exactly one of your form controllers should have the **Is mapped**
**to app Shell** property set to true. This property is used to specify
the primary form on the page. The primary form is responsible for
handling global events. You shouldn't set the property to true for


more than one form controller or have zero form controllers with the
property set to true.


7. Open the page containing one or more forms.


8. In the content tree, select a form.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-420-1.png)


9. In the configuration panel, on the **Configure** tab, select **Form**
**Controller** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-421-1.png)


10. On the **Edit Form Controller** pop-up, scroll down in the **Form Controller**
list to find the **Is mapped to App Shell** option.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-421-2.png)


11. Select or clear the option for each form component on the page to
confirm that exactly one form controller is mapped to the app shell.


**Advanced form event handling**


Experienced developers with knowledge of conflict event handling may
find the following details useful.


If isMapped to app shell is set to true, the form handles these events
automatically:


**Screen Status Changed**


**•** Description: Action to indicate that a form is dirty.


**•** Output: `CTRL_RECORD#SCREEN_STATUS_CHANGED`


**Update Configuration Menu Requested**


**•** Description: Action to set record configuration menu items on the
avatar menu.


**•** Output: `CTRL_RECORD#UPDATE_CONFIGURATION_MENU_REQUEST`


**Phone Requested**


**•** Description: Action to make a call when the CTI plugin is enabled.


**•** Output: `CTRL_RECORD#PHONE_REQUESTED`


**Form Loading State Changed**


**•** Description: Action to show a loading spinning when that form is
loading data.


**•** Output: `CTRL_RECORD#FORM_LOADING_STATE_CHANGED`


For detailed information about the Form component and its properties,
[see Form Overview on the ServiceNow Developer Site.](https://developer.servicenow.com/dev.do#!/reference/next-experience/washingtondc/now-components/form record page/overview)

## **Create modals in UI Builder**


Use modals in UI Builder with components to provide alerts or calls to
action for a user. UI Builder comes with modals to save time and effort.


**What Modals are**


Modals, also known as dialogs, are windows that overlay another content
window. Modals take control of the user experience. Users cannot
interact with the overlaid window until the modal is closed. Modals can
contain different types of content such as:


**•** Static text


**•** Dynamic text


**•** Forms


**•** Images


**•** Buttons


UI Builder has preconfigured modals available. You can add a modal to
your component. Then, configure the content of the modal, and how it
displays on the screen. Add an event handler to the modal to perform
an action when a user selects it. The action can alert a user about
something, or ask a user to confirm an action. A modal is a way to ensure
that a user knows what is happening. For example, a modal may ask a
user to confirm a selection before continuing whatever action they are
performing on the main page.


**Modal Anatomy**


Modals in UI Builder can have:


**•** Modal header


**•** Modal content


**•** Close dialog button (no action taken by the modal)


**•** At least one Modal button (action can be taken by the modal)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-424-1.png)


**Modal types**


Different types of modals are available in UI Builder, as shown in the
following table.


|Modal type|Description|
|---|---|
|Alert|An Alert modal provides<br>information relating to the<br>component action. For example,<br>when a user presses a delete<br>button, you could have an alert<br>pop-up that lets the user know<br>they cannot undo a delete action.|
|Confirm|A Confirm modal asks a user to<br>confirm the component action.<br>For example, when a user presses<br>a delete button, the user would<br>have to confirm the deletion of<br>data. You can choose the confirm<br>options from the primary and|


**Modal type** **Description**


|Col1|secondary button label fields, such<br>as Yes/Cancel.|
|---|---|
|Confirm and destroy|A Confirm and destroy modal is<br>more directive, usually relating to<br>deleting or erasing content. It lets<br>the user know the seriousness of<br>an action, and asks them whether<br>they want to proceed with the<br>action.|
|Custom|Custom modals address scenarios<br>that are not handled using<br>the standard modals. Custom<br>modals can be thought of as<br>a container component on a<br>modal. You can add a custom<br>layout, components, events, and<br>data resources just like you do<br>on a page. The custom modal<br>uses layouts to let you fully design<br>what information you want in<br>the modal. Layouts also decide<br>where the information sits within<br>the modal screen. You can use<br>Cascading Style Sheets (CSS)<br>styling to change the visual look of<br>the modal.|
|iframe|Use iframe to bring content into<br>your modal from existing iframe<br>content from a URL and data.|
|Modal viewport|Dynamically pass content into your<br>viewport modal through an event<br>binding using a client script.|


**Event handlers and modals**


Expose events to modals to handle call-to-action events. For example, a
primary action, secondary action, and so on. You configure the data by


adding an event handler and invoking a data resource. It is as simple as
adding a new event handler for the component that has a modal. Or
you can add an event handler to the modal itself. You select the event
that you want associated with the component or modal and add it. See
Add modal to component for detailed instructions.


**•** Add modal to component


Learn how to add a modal in UI Builder. A modal is a window that
appears when you click a component. For example, a modal might
display when a delete button component is clicked, prompting the user
to confirm deleting a record.


Learn how to add a modal in UI Builder. A modal is a window that
appears when you click a component. For example, a modal might
display when a delete button component is clicked, prompting the user
to confirm deleting a record.


**Before you begin**


Role required: ui_builder_admin


**About this task**


A modal is a screen that appears when an event handler is triggered by
an event such as a button being clicked. The following procedure shows
an example of how to add a Confirm modal and an associated event
handler to a button component.


**Procedure**


1. Navigate to **All > Now experience framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open or create a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a modal to the page.


a. Select the **+** icon in the content tree next to **Modals and**

**popovers** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-427-1.png)


b. Choose a modal type such as **Confirm** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-427-2.png)


|Modal type|Description|
|---|---|
|Alert|An Alert modal provides<br>information relating to the<br>component action. For<br>example, when a user presses<br>a delete button, you could<br>have an alert pop-up that lets<br>the user know they cannot<br>undo a delete action.|
|Confirm|A Confirm modal asks a user<br>to confirm the component<br>action. For example, when a<br>user presses a delete button,<br>the user would have to<br>confirm the deletion of data.<br>You can choose the confirm<br>options from the primary and<br>secondary button label fields,<br>such as Yes/Cancel.|
|Confirm and destroy|A Confirm and destroy modal<br>is more directive, usually<br>relating to deleting or erasing<br>content. It lets the user know<br>the seriousness of an action,<br>and asks them whether they<br>want to proceed with the<br>action.|
|Custom|The Custom modal uses<br>layouts to let you fully design<br>what information you want<br>in the modal. Layouts also<br>decide where the information<br>sits within the modal screen.<br>You can use Cascading Style<br>Sheets (CSS) styling to change<br>the visual look of the modal,<br>such as background color.|


|Modal type|Description|
|---|---|
|iframe|Use iframe to bring content<br>into your modal using existing<br>iframe content from a URL and<br>data.|
|Modal viewport|Dynamically pass content into<br>your viewport modal through<br>an event binding using a<br>client script. SeeBind an event<br>to a component for more<br>information on binding an<br>event to a component.|


c. Configure the modals as shown in the table.


Configure each modal differently, depending on what the
modal requires. Change what information goes into the modal,
the size of the modal, and how it looks. You can add an event
handler to the modal that performs the action for the modal,
such as opening or closing the modal.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-429-1.png)


|Modal|Configuration Select Small, Medium,|
|---|---|
||Select**Small**, **Medium**,<br>**Large**, or**Fullscreen**.<br>**•** Enable or disable**Prevent**<br>**Default Button Action**,<br>depending on whether<br>you want the modal to<br>close based on the default<br>action.<br>**•** Enable or disable**Defer**<br>**modal content loading**. If<br>you disable it, the modal<br>loads with the page. If<br>you enable it, the modal<br>doesn't load when the<br>page loads.<br>**•** Select**Events > Add event**<br>**mapping** to add an event<br>handler to the modal.<br>**•** Select an event handler<br>to apply to the modal,<br>then select**Add** to add<br>it to the page. Choose<br>from inherited or page-<br>level event handlers.<br>Event handlers perform an<br>action such as open or<br>close a modal. Depending<br>on the modal type, you<br>can refresh data for the<br>App Shell data source, the<br>user session for GraphQL,<br>or a user session for<br>Transform.|
|Confirm|**•** Add a header, which is the<br>title of the modal.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-430-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-431-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-431-1.png)


|Modal|Configuration • Select Events > Add event|
|---|---|
||**•** Select**Events > Add event**<br>**mapping** to add an event<br>handler to the modal.<br>**•** Select an event handler<br>to apply to the modal.<br>Choose from inherited or<br>page-level event handlers.<br>Event handlers perform an<br>action such as open or<br>close a modal. Depending<br>on the modal type, you<br>can refresh data for the<br>App Shell data source, the<br>user session for GraphQL,<br>or a user session for<br>Transform.|
|Confirm or destroy|**•** Add a header, which is the<br>title of the modal.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-432-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-433-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-433-1.png)


|Modal|Configuration • Select Events > Add event|
|---|---|
||**•** Select**Events > Add event**<br>**mapping** to add an event<br>handler to the modal.<br>**•** Select an event handler<br>to apply to the modal.<br>Choose from inherited or<br>page-level event handlers.<br>Event handlers perform an<br>action such as open or<br>close a modal. Depending<br>on the modal type, you<br>can refresh data for the<br>App Shell data source, the<br>user session for GraphQL,<br>or a user session for<br>Transform.|
|Custom|**•** Choose a layout for your<br>modal. You can use a|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-434-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-435-2.png)


flexbox or CSS grid layout.
These layouts let you add
content in your modal
however you want.


**•** Use styling options
to change how your
modal looks. You can
apply any standard CSS
styling to your modal,
such as background
color and padding. For
more information about
styling, see Change the
default appearance of
components.


**•** Add components to the
containers within the

custom modal.


**•** Select **Events > Add event**
**mapping** to add an event
handler to the modal.


**•** Select an event handler
to apply to the modal.
Choose from inherited or
page-level event handlers.
Event handlers perform an
action such as open or
close a modal. Depending
on the modal type, you
can refresh data for the
App Shell data source, the
user session for GraphQL,
or a user session for

Transform.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-435-3.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-436-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-436-1.png)


|Modal|Configuration Choose from inherited or|
|---|---|
||Choose from inherited or<br>page-level event handlers.<br>Event handlers perform an<br>action such as open or<br>close a modal. Depending<br>on the modal type, you<br>can refresh data for the<br>App Shell data source, the<br>user session for GraphQL,<br>or a user session for<br>Transform.|
|Modal viewport|**•** Choose the size of the<br>modal on the screen.<br>Select**Small**, **Medium**,<br>**Large**, or**Fullscreen**.<br>**•** Enable or disable**Hide**<br>**Padding**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-437-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-438-3.png)


**•** Enable or disable **Hide**
**Close Button** . If you enable
it, the close button does
not display in the modal.


**•** Enable or disable **Defer**
**modal content loading** . If
you disable it, the modal
loads with the page. If
you enable it, the modal
doesn't load when the
page loads.


**•** Select **Events > Add event**
**mapping** to add an event
handler to the modal.


**•** Select an event handler
to apply to the modal.
Choose from inherited or
page-level event handlers.
Event handlers perform an
action such as open or
close a modal. Depending
on the modal type, you
can refresh data for the
App Shell data source, the
user session for GraphQL,
or a user session for

Transform.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-438-2.png)


5. Add a component to your page to trigger the modal you just added,
such as a button component.
See Add and configure components for more information.


6. Select the **Events** tab in the configuration panel.


7. Select **+ Add event handler** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-439-1.png)


8. Select **Open or close modal dialog** .


9. Select the modal you created in the previous steps using the **Modal**
drop-down.


10. Click **Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-440-1.png)


11. When you finish configuring the modal, close it.


Notice in the content tree that the modals you create sit above the
body of your page structure.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-441-1.png)


12. Click **Save** .

## **Extend your UI experience with viewport components**


Viewports are specialized components that enable you to extend your
experience without needing to own the parent page in UI Builder.
You can work with viewports in three ways. You can add a viewport
component or a viewport-enabled tab to a page, or add a viewport to
the Contextual sidebar component.


Add a viewport component to your page to create separate content
even if you do not own the content of the page itself. Create subpages,
specify audiences, or customize content with different data, routes, and
screens. For more information about viewport components, see Add a
viewport component to your page.


You can replace Tabs components with Viewport-enabled tabs as a
way to display third-party custom data, assign audiences, and create


variants. For more information about viewport-enabled tabs, see Replace
a tab with a viewport-enabled tab.


Use the **Edit content** mode of UI Builder to add viewports or tab sets
to a page or Contextual sidebar component. Edit tabs in a Contextual
sidebar component as you would on a page using the **Config** panel. The
main difference is, when you are in the **Edit content** mode of a tab, the
page management area changes to **Tab management** .


Select the menu icon to edit your tab settings, or change the
required or optional parameters.


Add viewport modals to your experience to embed subpages or other
experiences within a modal in your parent page/experience. For more
information about adding viewport modals to your experience, see Add
a viewport modal to your experience.


**•** Add a viewport component to your page


Add a viewport component to your page and create a subpage to
create separate content on the page.


**•** Add a viewport modal to your experience


Add a viewport within a modal in your experience.


**•** Replace a tab with a viewport-enabled tab


Convert a tab on a page to a viewport-enabled tab. Use viewportenabled tabs to display third-party custom data, assign audiences, and
create variants.


Add a viewport component to your page and create a subpage to
create separate content on the page.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open the editor for the page variant that you want to add the
viewport to.
If you haven't created a page for your experience, follow the steps to
Create a page in UI Builder.


4. Select **+ Add content** in the content tree.


5. Select a **Single column** layout.


6. Next, select the **+** icon in the column to open the toolbox.


7. Enter `viewport` in the search box.


8. Select **Viewport** .


Viewport component

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-444-1.png)


9. Select the viewport component in the content tree.


10. Select **+ Add** in the configuration panel.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-445-1.png)


11. Select a page collection from the list or create a collection by
selecting **+ Create collection** .
For more information on creating your own page collection, see
Create a page collection across multiple UI pages.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-446-1.png)


12. Select **Add** .
The page collection displays in the **Page collections** section of the
configuration panel. Only one page of the page collection displays
in the staging area.


13. Select **Save** .


14. Locate the viewport ID and route.


You can see the ID and route in the Config panel as shown in the
following figure.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-447-1.png)


15. Add a component to your page to open the viewport you just
added, such as a button component.
For more information, see Add and configure components.


16. Select the **Events** tab in the configuration panel.


17. Select **+ Add event handler** to view the viewport.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-447-2.png)


18. From **Page-level event handlers**, select **UXF Macroponent Viewport**
**Load Requested** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-448-1.png)


19. In the **viewportElementID** element, replace the `null` value with the
viewport ID that you located in a previous step.
In this example, it is, `"viewport_1"` .


20. Select **Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-449-1.png)


21. Select **Save** .


22. View and test your page by selecting .


Add a viewport within a modal in your experience.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Use viewport modals to embed subpages or other experiences within
a modal in your parent page or experience. Viewport modals can
be opened via events or scripts. Viewport modals are limited to one
subroute per viewport modal. You can create additional viewport
modals for extra routes.


**Note:** Legacy viewport modals cannot be upgraded and must be
recreated to take advantage of the new functionality.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information.


3. Open or create a page.
If you open an existing page, ensure you are in the same scope as
the original page. If not, change the scope before you start editing
the page. Application scoping protects applications by identifying
and restricting access to application files and data. Administrators set
the scope to specify what parts of an application are accessible to
other applications. Application scope protects data and application
files. See Learn about security and roles for more information on
application scope.


4. Select **+ Add content** in the content tree.


5. Select a **Single column** layout.


6. Select **+** next to **Modals** in the content tree.


7. Select **Viewport Modal** in the list.


Viewport Modal

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-451-1.png)


A viewport model appears above your page.


8. Click **Save** .


9. Select the viewport in the content tree.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-452-1.png)


10. Select **+ Add** next to **Page collections** in the configure tab.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-453-1.png)


11. Select a page collection or create a new one.
For more information, see Create a page collection across multiple UI

pages.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-454-1.png)


12. Click **Add** .


13. Click **Save** .


14. Add a component that opens the viewport modal.


The following example uses a button to open the viewport modal.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-455-1.png)

15. Select the **Events** tab.


16. Select **+ Add event handler** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-456-1.png)


17. Select **Open or close modal dialog** .


18. Enable **Open modal dialog** .


19. Select the viewport modal that you created in the **Modal** dropdown.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-456-2.png)


The **Viewport ID** auto populates.


20. Select **Add** .


21. Select **Save** .


22. View and test your page by selecting .


Convert a tab on a page to a viewport-enabled tab. Use viewportenabled tabs to display third-party custom data, assign audiences, and
create variants.


**Before you begin**


Role required: admin


**About this task**


Replace your tab or tabs with viewport-enabled tabs.


**Note:** Replacing a tab with a viewport-enabled tab is a permanent
and one-way process. You lose any existing tab content and must
recreate the viewport tab content.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-457-1.png)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page with existing tabs, or add a **Tabs** component
to your page.
Tabs component

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-458-1.png)


For more information on how to add a Tabs component to a page,
see Add tabbed content to UI Builder pages.


4. Select the tabs component that you want to replace with viewport
tabs in the content tree.


5. Select **Replace with viewport tabs** in the configuration panel.


**Note:** Replacing a tab with a viewport-enabled tab is a
permanent and one-way process. You lose any existing tab
content and must recreate the viewport tab content.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-459-1.png)


6. Select **Replace with viewport tabs** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-460-1.png)


7. Click **Edit content** to add a viewport-enabled tab.


Edit content

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-461-1.png)


For more information on viewport components, see Add a viewport
component to your page.


8. Select **Save and continue** .
The sub-page overview page appears.


9. Select **Create new page.**


10. In the **Name** field, enter a name for your viewport-enabled tab.


11. Keep the default path, or change it to your preference.


12. Select **Continue** .


13. In the **Name** field, enter a name for the page variant or leave it as
**Default** .


14. Add one or more audiences for this page.
If an audience you need is not listed, you can choose the **View all**
**available audiences** to create one.


15. (Optional) Declare conditions for when to display the page or tab
by either using the provided dropdown menus or writing an encoded
query string.


[For more information on writing encoded queries, see Encoded query](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)
[strings.](https://www.servicenow.com/docs/csh?topicname=c_EncodedQueryStrings&version=zurich&pubname=zurich-platform-user-interface)


16. Select **Open in editor** .


17. Add components to your tab as you would to a page.


18. Add an event handler to any components to make them perform
actions, such as loading page content.
For more information about event handlers, see Manage actions in UI
Builder pages.


19. Select **← Back to (name of page)** to return to your original page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-462-1.png)


20. In **Data driven tabs**, select a data source to bind data to your
viewport-enabled tab using data resources to dynamically expose
your data from tables and records.


You then bind these data properties to components in your tab.
For more information about using data resources, see Dynamically
expose data in UI Builder pages (advanced feature).

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-463-1.png)


21. Choose where the viewport-enabled tab labels appear on the page
and decide whether to hide tab labels so you only see the icons.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-464-1.png)

## **Create popovers in UI Builder**


Use popovers on a UI Builder page to overlay contextual information or
functionality to help users complete tasks.


A popover is a small window or dialog box that appears above a UI
Builder page and contains additional information, options, or actions
related to the content or task at hand. Add components to a popover in
the same way you add modals to a page.


You can place popovers anywhere on a UI Builder page where you think
additional information helps the users. Popovers are intended to provide
small pieces of information or links to related content, so you should limit
the amount of information or functionality within a popover because the
popover only displays when a user is interacting with it.


You can make popovers visible or hidden with event mapping, such as
triggering a popover to appear when selecting a button or pointing to a
part of the page. For more information, see Define map events.


Informational popover

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-465-1.png)


**Add popover to a UI Builder page**


Learn how to add a popover in UI Builder. A popover is a container
that appears above a page when you click a component. For example,
a popover might display contact information when selecting a persons
name in a list.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now experience framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open or create a page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a component to your page that you want to trigger a popover,
such as a button component.
See Add and configure components for more information.


5. Select the **Events** tab in the configuration panel.


6. Select **+ Add event handler** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-466-1.png)


7. Select **Open Popover** .


8. Select **Create a new popover** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-467-1.png)


9. Select **Add** .
The popover appears above the stage.


10. Add components to the popover by selecting the **+** icon.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-468-1.png)


11. When you finish configuring the popover, close it.


Notice in the content tree that the popovers you create sit above
the body of your page structure.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-469-1.png)


12. Click **Save** .


13. Select **Preview** in the UI Builder header.


14. Click on the button to test the popover.

## **Create modeless dialogs in UI Builder**


Use modeless dialogs on a UI Builder page to add a floating window that
enables you to interact with both the window content and the page
content below.


The Modeless Dialog component is a floating window containing
components and content that appears over a UI Builder page. You can


do actions in the modeless dialog while still viewing and interacting with
the page below. Multiple modeless dialog windows can be added to a
single page. Modeless dialogs can be resized, moved to a new position
on a page, and minimized.


Modeless dialogs are different than modals, which pop up but block
interaction with the page until the modal is closed. Modeless dialogs
are also different than popovers, which close after you click outside the

popover.


Common modeless dialog use cases include creating a record,
composing an email, using chat, adding work notes or comments,
reading help information, or adding/viewing attachments in the
modeless dialog.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-470-1.png)


**Anatomy of a modeless dialog**


A modeless dialog consists of three parts:


**•** When you add a modeless dialog to a page, the header includes
a preconfigured minimize icon, expand icon, and close icon. Other
actions can be configured if needed, for example, configure an action
in a button to open the modeless dialog in a new tab.


**•** Add any component from the UI Builder toolbox, for example, Email
composer, Attachments, or Agent chat, into the body. You can apply
layouts and configure the component as if you were adding the
component to a page.


**•** If needed, provide additional buttons or content in the footer at the
bottom of the modeless dialog.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-471-1.png)


**•** Add modeless dialog to a UI Builder page


Learn how to add a modeless dialog in UI Builder. A modeless dialog is
a floating window containing content above a page.


**•** Add modeless dialog event to a UI Builder page


Learn how to add and configure a modeless dialog event, such as
open, close, or minimize in UI Builder. A modeless dialog is a floating
window containing content above a page.


Learn how to add a modeless dialog in UI Builder. A modeless dialog is a
floating window containing content above a page.


**Before you begin**


Role required: ui_builder_admin


The following steps walk you through the process of configuring a button
to open a modeless dialog containing the Attachments component.


**Note:** The procedure outlined here is just one example of how
to use modeless dialogs. There are infinite possibilities. Add and
configure modeless dialogs to meet your business needs.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open or create a page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. In the content tree, move your mouse to **Modeless dialogs**, select the
+ icon, and select the **Modeless dialog** component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-473-1.png)


5. If the modeless dialog doesn't appear on the stage automatically,
select the new modeless dialog named **Modeless dialog default** in
the content tree.


6. In the configuration panel **Configure** tab, view the presets that were
added automatically with the modeless dialog, for example, the
width, height, position, and enable drag setting.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-474-1.png)


All of these preset properties can be edited, if necessary.


**Note:** For more information about Modeless Dialogs advanced
[properties, see the ServiceNow Developer site.](https://developer.servicenow.com/dev.do#!/reference/next-experience/vancouver/now-components/now-modeless-dialog/overview)


7. In the data resources drawer, the **Modeless dialog** controller was
added automatically.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-475-1.png)


8. In the content tree, select **+ Add content** under **Modeless dialog**
**default > actions** to add content to the modeless dialog header.


9. Search for and select the **Stylized text** component.


10. In the **Stylized text** configuration panel, select **None** to configure the
component manually.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-475-2.png)


If the **Record subheading** preset was automatically added, select the
drop-down arrow, select **None**, and select **Remove** on the **Configure**
tab.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-476-1.png)


11. If not open already, select **Configure** to open the configure tab.


12. In **Text**, remove the sample text and type `Add Attachments` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-476-2.png)


13. Select **Save** in the UI Builder header.


14. In the content tree, select **+ Add content** under **Modeless dialog**
**default > content > Container** to add content to the modeless dialog
body.


15. Select the **Attachments** component.


16. In the **Attachments** configuration panel, if not selected already,
select **Record attachments** and **Apply** to configure the component
with a preset.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-477-1.png)


For more information about configuring the Attachments
[component, see the ServiceNow Developer site.](https://developer.servicenow.com/dev.do#!/reference/next-experience/vancouver/shared-components/now-record-common-attachments-connected/overview)


17. You could add content to the modeless dialog footer, but in this
example leave the footer empty.


18. Select **Save** .
Notice in the content tree that the modeless dialog and all of its
components are listed above the **Body** of your page structure. Also,
the **Minimized dialogs dropdown** component is added to the page
automatically (and is listed under the **Body** in the content tree) to
provide the functionality for the minimize icon in the modeless dialog
header.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-478-1.png)


19. In the content tree, select **Body** .


20. Add a button component and configure it to open the modeless
dialog.


a. In the content tree, select the **Menu** icon next to **Body** and select
**Add content** .


b. On the **Layouts** tab, select **Single column** .
A new column layout containing a single column is added to the
bottom of the page.


c. On the stage, select the + icon in the new column layout.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-478-2.png)


d. Search for and select the **Button bare** component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-479-1.png)


e. In the configuration panel, on the **Configure** tab, select **None** to
configure the component manually.


f. Select the **Events** tab in the configuration panel.


g. Select **+ Add event handler** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-479-2.png)


h. In the list at left, select **Open Modeless dialog** (you may need to
scroll down in the list).


i. Type `Attachments` in **Minimized Heading** .


j. Select **Modeless dialog default** in **Modeless dialog** .
There are other options that can be configured here, including a
heading and a category.


k. Select **Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-480-1.png)

l. Select the **Configure** tab.


m. Type `Add Attachments` in **Label** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-480-2.png)


21. Select **Save** .


22. Select the drop-down arrow next to **Preview** in the UI Builder header
and select **Open URL path** in the list.


23. Select the **Add Attachments** button to test the modeless dialog.
The modeless dialog opens above the main page with the heading
at the top and the Attachments component below.


24. To test the minimize functionality, select the minimize icon on the
modeless dialog.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-481-1.png)


The modeless dialog is minimized and can be accessed from the
Minimized dialogs drop down.


25. Select the minimized dialogs icon and then select **Attachments** to
open the modeless dialog window again.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-481-2.png)


Learn how to add and configure a modeless dialog event, such as open,
close, or minimize in UI Builder. A modeless dialog is a floating window
containing content above a page.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open or create a page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a modeless dialog to the page.
For more information about how to create a modeless dialog, see
Add modeless dialog to a UI Builder page.


5. Add a component to the page, such as a button, to take action on
the modeless dialog.
For more information about how to create a button that interacts
with a modeless dialog, see Add modeless dialog to a UI Builder

page.


6. Select the button component in the content tree or on the stage.


7. In the configuration panel, select the **Events** tab.


8. Select **+ Add event handler** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-482-1.png)


9. From the Event handler preview window, select an action to assign to
the button.
There are five modeless dialog event handlers available.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-483-1.png)


**Note:** For any of the event handlers, select **Script** in the **Mode**
drop-down if you prefer to work in the script editor.

|To add a modeless dialog event<br>handler|Do the following|
|---|---|
|Open Modeless Dialog|Opens a modeless dialog. For<br>example, add a button labeled<br>Compose email and configure<br>the button to open a modeless<br>dialog containing the Email<br>composer (mini) component.<br>**• Heading**: Type a heading for<br>the modeless dialog.<br>**• Minimized Heading**: Type a<br>heading that is displayed<br>when a user selects<br>the minimized dialogs drop-<br>down icon on the page.|


|To add a modeless dialog event<br>handler|Do the following|
|---|---|
||**• Category**: Type a category<br>name to group the<br>modeless dialog.<br>**• Modeless Dialog**: Select the<br>modeless dialog to open.<br>**• Single instance**: Select<br>this option to enable<br>users to open only one<br>instance of the modeless<br>dialog. Leave this option<br>unselected to enable<br>users to open multiple<br>instances of the modeless<br>dialog. For example, if<br>the button opens a<br>modeless dialog containing<br>the Email composer (mini)<br>component and you don't<br>select the single instance<br>option, users can open<br>multiple modeless dialog<br>windows to compose email<br>messages.<br>**• Modeless Dialog Instance**<br>**ID**: If you select the**Single**<br>**instance** option, specify the<br>modeless dialog instance<br>ID that should be opened<br>on click. Move your mouse<br>over the field and select<br>the**Bind data** icon. In<br>**Data types** select**Modeless**<br>**Dialog**. Drag the instanceID<br>pill to the top section and<br>select**Apply**.<br>**• When to trigger** (Advanced<br>option): Select**Always**|


|To add a modeless dialog event<br>handler|Do the following|
|---|---|
||to have the component<br>(in this example, the<br>button) always open the<br>modeless dialog. Select<br>**Conditionally** to add an<br>event handler condition.<br>For more information about<br>event handler conditions,<br>seeSupported functions in<br>the UI Builder component<br>formula editor.|
|Close Modeless Dialog|Closes a modeless dialog. Use<br>this option if you want to<br>configure a component, such<br>as a button, to close the<br>modeless dialog from outside<br>the modeless dialog window.<br>**• Modeless Dialog Instance**<br>**ID**: Specify the modeless<br>dialog instance ID that<br>should be closed on click.<br>**• When to trigger** (Advanced<br>option): Select**Always**<br>to have the component<br>(in this example, the<br>button) always close the<br>modeless dialog. Select<br>**Conditionally** to add an<br>event handler condition.<br>For more information about<br>event handler conditions,<br>seeSupported functions in<br>the UI Builder component<br>formula editor.|
|Minimize Modeless Dialog|Minimizes an open modeless<br>dialog. Use this option if<br>you want to configure a|


|To add a modeless dialog event<br>handler|Do the following|
|---|---|
||component, such as a button,<br>to minimize the modeless dialog<br>from outside the modeless<br>dialog window.<br>**• Modeless Dialog Instance**<br>**ID**: Specify the modeless<br>dialog instance ID that<br>should be minimized on<br>click.<br>**• When to trigger** (Advanced<br>option): Select**Always**<br>to have the component<br>(in this example, the<br>button) always minimize<br>the modeless dialog. Select<br>**Conditionally** to add an<br>event handler condition.<br>For more information about<br>event handler conditions,<br>seeSupported functions in<br>the UI Builder component<br>formula editor.|
|Update Modeless Dialog|Updates the specified fields on<br>a modeless dialog. For example,<br>add a button labeled Update<br>Heading to the footer of a<br>modeless dialog and configure<br>the button to update the<br>heading of the component in<br>the modeless dialog.<br>**• Heading**: Type new heading<br>text for the modeless dialog<br>that should be added when<br>the button is selected.<br>**• Minimized Heading**: Type<br>new minimized heading text|


|To add a modeless dialog event<br>handler|Do the following|
|---|---|
||that should be added when<br>the button is selected.<br>**• Category**: Type a new<br>category name that should<br>be added when the button<br>is selected.<br>**• Modeless Dialog**: Select the<br>modeless dialog to update.<br>**• Modeless Dialog Instance**<br>**ID**: Specify the modeless<br>dialog instance ID that<br>should be updated on click.<br>**• Is Dirty**: Select this option to<br>mark the modeless dialog as<br>dirty.<br>**• When to trigger** (Advanced<br>option): Select**Always**<br>to have the component<br>(in this example, the<br>button) always update the<br>modeless dialog. Select<br>**Conditionally** to add an<br>event handler condition.<br>For more information about<br>event handler conditions,<br>seeSupported functions in<br>the UI Builder component<br>formula editor.|
|Dirty Modeless Dialog|Marks a modeless dialog as<br>dirty.<br>**•** In**Modeless Dialog Instance**<br>**ID**, specify the modeless<br>dialog instance ID to mark<br>as dirty.|


|To add a modeless dialog event<br>handler|Do the following|
|---|---|
||**• When to trigger** (Advanced<br>option): Select**Always** to<br>have the component (in<br>this example, the button)<br>always marked as dirty.<br>Select**Conditionally** to add<br>an event handler condition.<br>For more information about<br>event handler conditions,<br>seeSupported functions in<br>the UI Builder component<br>formula editor.|


10. Select **Add** .


**Result**


The configured event handler displays in the configuration panel **Events**
tab for the component.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-488-1.png)

## **Configure alerts to auto-dismiss**


Set alerts to automatically clear after a specified time period.


**Before you begin**


Role required: ui_builder_admin


**About this task**


You can configure alerts to auto-dismiss in two ways:


**•** Experience settings: apply auto-dismiss rules to all alerts of a specific
type


**•** Events: add an event to override experience settings for specific alerts


**Important:** You must first enable auto-dismiss at the experience
settings level before you can configure it at the event level.


Configurations made through an event take priority over those made
in the experience settings. For example, in the experience settings, you
might set all **Positive** alerts to auto-dismiss after 5 seconds. Then, for
a specific **Positive** alert, you could override this initial configuration by
adding an event that sets it to auto-dismiss after 10 seconds, or to disable
auto-dismiss entirely.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select **View experience settings** .


4. Under **Configure alerts**, select the **Auto-dismiss** option next to the
alert type you wish to configure.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-490-1.png)


For this example, select the **Auto-dismiss** option next to the **Info** alert
type and enter `5` in the **Timeout (seconds)** field. **Info** alerts disappear
after 5 seconds.


5. Select **Save** .


6. Return to the experience view.


7. Create or open a page.


8. In the content tree, select **+ Add content** .


9. Select a **Button** component and select **Add** .


10. In the configuration panel, select the **Events** tab.


11. Under **Button clicked**, select **Add handler** .


12. Select **Add alert notifications** and select **Continue** .
The **Configure** dialog enables you to edit multiple alerts in one place
and displays a preview of the alert being edited. You can select
the **+** to add more alerts, then select the alert in the dropdown to
configure it.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-491-1.png)


For this example, leave the alert **Type** as **Info** .


13. At the bottom of the **Configure** dialog, under **Auto-dismiss**, enter `10`
in the **Timeout** field.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-492-1.png)


This specific **Info** alert disappears after 10 seconds.


14. (Optional) You can also clear the check box to turn off auto-dismissal
for this individual alert.


**Note:** Other alerts of the same type retain the initial
configuration in the experience settings until overridden through
an event.


15. Select **Add** .


**Result**


Alerts of the selected type are now set to auto-dismiss after the specified
time period.


## Manage actions in UI Builder pages


Learn how to work with events so that you can add actions to
components, pages, data resources, and declarative actions in UI
Builder.


**Actions in UI Builder**


UI actions tell UI Builder what to do when an event is triggered. An event
is an action a user takes or occurrence that happens on a page. Use UI
actions to create interactive, user-friendly interfaces that help your users
complete tasks. Each component has its own events associated with it.
Events include:


**•** User clicks a data visualization


**•** Page successfully fetches data


**•** User selects a radio button


**•** Page loads


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-494-1.png)


**Events in UI Builder**


Use an event to add actions to your components, pages, and data

resources.


**•** A component event is an action that you set up for a component.
You set up an event handler to configure that component action. For
example, you can add a button component to your UI Builder page.
Then, you can add an event handler to apply an action for that button,
such as going to a web page.


**•** Page events perform actions for the entire page. You can configure
the following page events:


**•** Page event mappings. Add, remove, or clear alert notifications on

your page.


**•** Variant event mappings. Add, remove, or clear alert notifications on
your page variant.


**•** Dispatched events. Create dispatched events for your page to
create relayed event mappings that model events after a parent
event handler. Select a target parent event handler to model the
payload fields after it.


**•** Handled events. A handled event is an event that is exposed and
available for use by other users. After you create a handled event, it
is available under Page event mappings for other users to use. You
can also set up payload fields that you create manually or choose a
template for your handled event, such as an open or close a modal
dialog.


**•** Data resources events map data resources to notify information about
when data is fetched.


**•** Events for a page or component do nothing until the event is mapped
to one or more event handlers.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-495-1.png)


**Event mapping in UI Builder**


Map actions to events such as clicking a button or filling in a field.
An event mapping is the process that enables you to map an event's
payload or contextual values to the object or handler that acts on that
event.


For more information about event mapping, see Define map events.


**Event handlers in UI Builder**


An event handler is an action performed when an event occurs. By
mapping an event handler to an event, you are specifying which action
or actions to take when the event occurs. Use an event handler to
configure an action for your UI Builder page or the components on the
page. For example:


**•** Clicking a data visualization opens a list of records represented in the
visualization


**•** Fetching data successfully for a list opens an alert that indicates the
data fetch was successful


**•** Selecting a radio button adjusts the filter for a list on the page


**•** Loading a page opens a modal to confirm acceptance of cookies
before proceeding


When you add an event handler to a UI Builder page or component,
you can choose different types of event handlers. For example, a Button
component can have the following types of event handlers:


**•** Inherited event handlers. An inherited event handler is exposed from
the page that you are working in. If you are in the parent UI Builder
page, an inherited event handler could be exposed from the app shell.
The following table lists the different types of inherited event handlers
that you can use and what you can do with them.


**Inherited event handlers**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-496-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-497-1.png)


|Link to destination|Navigate to a destination.<br>• App routes: Link to another<br>page within an app, like a<br>home screen.<br>• External URL: Link to a website or<br>any external URL.<br>Sample script<br>return {<br>route: null, /* Pa<br>ge route, e.g. 'record' */<br>fields: null, /* R<br>equired params, e.g. {"tab<br>le":"incident","sysId":"X"<br>} */<br>params: null, /* O<br>ptional params, e.g. {"sel<br>ectedIndex" : 1} */<br>redirect: null, /<br>* ??? True/false? */<br>passiveNavigation<br>: null, /* Load in backgr<br>ound, e.g. 'false' */<br>title: null,<br>multiInstField: nu<br>ll,<br>targetRoute: null<br>, /* ??? */<br>external: null /*<br>??? True/false? */<br>};|
|---|---|
|Add parameters to URL|Add additional parameters to a<br>URL.<br>Sample script<br>~~`{ “selectedTabIndex” : 0 }`~~|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-498-1.png)


**•** Page-level event handlers. This type of event handler is common to all
pages, and you would use this handler type when you want to add or
clear page-level alert notifications. The following table lists the different
types of page-level event handlers that you can use and what you can
do with them.


**Page-level event handlers**


|Event handler|Description|
|---|---|
|Add alert notifications|Add a code snippet to send an<br>alert notification. For example:<br>~~`return {`~~<br>`  items: [{"type" : "inf`<br>`o", "message" : "Info mes`<br>`sage", "id" : "optionalID"`<br>`}] /* Types: info, warning`<br>`, error */`<br>`};`|
|Remove alert notification|Add code to call alert notification<br>IDs that you want to dismiss.<br>For example, click a button<br>to remove a page load alert<br>notification.|
|Clear alert notification|Add code to call all alert<br>notification IDs that you want<br>to dismiss. For example, click<br>a button to remove all alert<br>notifications.|
|Set loading state|Toggle loading on or off. For<br>example, you can toggle loading<br>on to load the page when you<br>click a button or toggle loading|


**Event handler** **Description**


|Col1|off to not load the page when a<br>button is clicked.|
|---|---|
|Update client state parameter|Declaratively set the client state<br>parameter. Let's say that you<br>have a client state parameter<br>that you set up with a value. You<br>can configure the Update client<br>state parameter event handler to<br>update the client state parameter<br>with a new value. For example,<br>you have a client state parameter<br>that is called**Greeting** that is set<br>up with`Hello` as the initial value.<br>You can add an Update client<br>state parameter event handler,<br>select the**Greeting** client state<br>parameter, and then enter a<br>new value like`Goodbye`. When<br>you click the button,**Goodbye**<br>replaces**Hello** on the page.|
|UXF macroponent viewport load<br>requested|Add to a component, such as<br>a button component, to open a<br>viewport. For more information,<br>seeAdd a viewport component<br>to your page.|


**•** Data resource handlers. This type of event handler triggers the fetching
or writing of data to the server.
You can refresh the app shell data source data on your UI Builder page
by clicking a button. For example, with a data resource handler, you
can do the following actions:


**•** Bind data to the description of an incident record.


**•** Change the value of the incident description.


**•** Add a button component to your page.


**•** Label the button as `Refresh incident` .


**•** Add a Look Up Record event handler for the button.


**•** Save your page.


**•** If the description of the incident record changes, click **Refresh** to
update the description on your page.


**•** Client scripts. Scripts that execute when an event is triggered on a
component. You create these scripts in the Client scripts section in
UI Builder. For more information, see Define and bind client scripts to
components.


**Binding events to components in UI Builder**


Bind event handlers to the events on a component. When you add
components to your UI Builder page, these components are not
configured to perform any action on your page. For example, a button
component is static and does not do anything until you bind an event
action to it, such as deleting a record. Some components have several
events where event handlers can be assigned. For example, on the list
component, you can assign a navigation handler to the Row clicked
event. You can also assign an open modal to the Data fetch failed
event. For more information, see Bind an event to a component.


**Binding events to UI Builder pages**


Bind a page-level event to execute event handlers on the page. For
example, use page-level events for page notifications, page load, or
when a page property changes. The assignment of the event handler
to the page-level event is similar to assigning handlers to events from
components.


You can bind event mappings using the following methods:


**•** Page event mappings. Add, remove, or clear alert notifications on your

page.


**•** Variant event mappings. Add, remove, or clear alert notifications on
your page variant.


**•** Dispatched events. Create dispatched events for your page to create
relayed event mappings that model events after a parent event
handler. Select a target parent event handler to model the payload
fields after it.


**•** Handled events. Add a handled event for an event that is exposed
and available for use by other users.


For more information, see Bind an event to a page.


**Binding events to data resources in UI Builder**


Bind event handlers to individual data resources on your UI Builder page.
For example, when a data resource successfully fetches new data, it
executes an event handler, like navigation, to take a user to the next
step in a flow. When a data resource successfully adds a record to a
table, it shows a success modal that uses the show modal event handler.
For more information, see Bind an event to a data resource.


**Binding events to declarative actions in UI Builder**


Bind data elements to add event actions to a declarative action
definition in **Actions & Components** in the ServiceNow AI Platform®. For
example, you could bind a data element to add an event action to
complete work on a table.


If you add a component to your UI Builder page that has a declarative
action, you must bind it to a handled event. The handled event creates
an action that is performed when a user selects the component. By
selecting **Configure declarative action event mapping**, you add a new
event handler to define what the declarative action does on the page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-502-1.png)


For more information, see Bind an event to a declarative action.


**•** Define map events


An event mapping in UI Builder is the process that enables you to map
an event's payload or contextual values to the object or handler that
acts on that event. The four event types are: component, page, data
resource, and declarative action.


**•** Event payloads in UI Builder


Use event payloads to link data to an action.


**•** Configure an event handler manually


Add an event handler to a page, component, data resource, or
declarative action within UI Builder so that your user can trigger an
action.


**•** Configure an event handler with Now Assist


Use Now Assist in UI Builder to configure event handlers. At present, you
can configure link to destination, open or close modal, and view load
requested event handlers using Now Assist in UI Builder.


**•** Bind events to add actions


After you have created events, you can bind them to actions on your
components, pages, data resources, and declarative actions.


**•** Disable component preset event mappings


You can disable event mappings that are automatically created by a
component preset.


**•** Delete an event handler


Delete an event handler that you no longer need in UI Builder.


**•** Delete an event mapping


Delete an event mapping that you no longer need in UI Builder.


**•** Add events to track components with unsaved changes


Locate dirty state components through event configuration.

## **Define map events**


An event mapping in UI Builder is the process that enables you to map
an event's payload or contextual values to the object or handler that
acts on that event. The four event types are: component, page, data
resource, and declarative action.


Event mapping is an important process within UI Builder. When you build
pages with components, you need those components to perform actions
for users. For example, if you add a button component to the page, a
button-clicked event must be mapped to an event handler. The event
handler performs a button-clicked action when it is selected by a user.


An example is when you add a data resource, such as a form, and have
an event handler notify the user when the form successfully loads.


**Event types**


The event types that are available are based on the component.
For example, declarative action events are available for specific
components, such as the Action bar and List components.


You choose a type of event based on what action you want to
perform on your page. For example, if you want to bind an action to
a component, such as a button loading a web page, you would use a
component event. If you want an event to apply to your whole page,
such as adding an alert notification to a page, you use a page event.
The following table describes each event type that is available in UI
Builder and provides some examples on how you can use the events.


**Event types and descriptions**


|Event type|Description|
|---|---|
|Component events|Action that you set up for<br>a component. You set up an<br>event handler to configure that<br>component action. For example,<br>add an event handler to apply<br>an action for a button, such as<br>going to a web page. For more<br>information on binding events to<br>components, seeBind an event to<br>a component.|
|Page events|Page event that performs an<br>action for the entire page. You<br>can configure the following page<br>events:<br>**•** Page event mappings.<br>**•** These event mappings are<br>saved on the page definition<br>record, which can be found|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-505-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-506-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-507-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-508-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-508-1.png)


|Event type|Description For more information on binding|
|---|---|
||For more information on binding<br>an event to a page, seeBind an<br>event to a page.|
|Data resource events|Events that are mapped to data<br>resources to provide notifications<br>about when data is fetched.<br>**•** Data Fetch Initiated. When a<br>data resource event is triggered,<br>the event handler executes the<br>data fetch process.<br>**•** Data Fetch Succeeded. When a<br>data resource event is triggered,<br>the event handler executes<br>the process to notify a user<br>when the data fetch completed<br>successfully.<br>**•** Data Fetch Failed. When a<br>data resource event is triggered,<br>the event handler executes the<br>process to notify a user if the<br>data fetch was unsuccessful.|


|Event type|Description|
|---|---|
||For more information on binding<br>an event to a data resource, see<br>Bind an event to a data resource.|
|Declarative action events|Bind data elements within UI<br>Builder to add event actions to a<br>declarative action.<br>You configure a declarative action<br>event mapping in the ServiceNow|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-510-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-511-1.png)


## **Event payloads in UI Builder**

Use event payloads to link data to an action.


Event payloads are pieces of data sent by a component when a
selected event is triggered. The data sent by an event can include the
type of event, timestamps, user actions, or resource data such as a SysID.
You can use event payloads in UI Builder to share information between
components on a page.


You can use this payload data when configuring an event handler so
that the resulting interaction can be linked to the emitted data. For
example, a SysID can be passed to other components on a page to
display information related to a specified record.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-512-1.png)


Each component and event has a unique set of payload options. Event
payloads may not be properly defined for each component. If that is
the case, define a client script so that the console logs payloads such as
`console.log(event.payload)` .


**Create an event with payloads to share information between**
**components**


Use event payloads in UI Builder to share information between
components on a page.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .


For more information, see Configure how users interact with your
applications in UI Builder.


3. Create or open a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a component that has events, such as the data visualization
component.
For more information about adding components to a page, see Add
and configure components.


5. To add an event handler to your component, select the **Events** tab.
For more information on how to add event handlers to your
component, see Manage actions in UI Builder pages.


a. To start the process of setting up an event handler for your
component, click **Add event mapping** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-514-1.png)


b. Select the event mapping that you want to configure from the
list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-515-1.png)


c. Select **Continue** .


d. From the Event handler preview section, select an event handler
to bind to your component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-516-1.png)

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-516-2.png)


e. Select **Continue** .


f. Select the **Create a new client state parameter** from the **Client**
**State Parameter Name** drop-down.


g. Enter a name in the **Name** field.


h. Select the type of client state parameter from the **Type** dropdown.


i. Enter a value in the **Initial value** field.


j. Select the bind data icon in the **Value to use after triggering**
**event** field.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-517-1.png)


k. Select the value you would like to bind to the triggered event.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-518-1.png)


l. Select **Apply** .


m. Select **Add** .
The data handler will appear below the event mapping in the
events tab.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-519-1.png)


6. Select the component you want to bind the client state parameter
to, in this example we will be using a heading component.


7. Select bind data icon in the field you want to bind the client state
parameter to.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-520-1.png)


8. Select **Client states** .


9. Select the arrow next to the client state parameter you want to bind.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-521-1.png)


10. Select **Apply** .


11. Select **Save** .


12. Select **Preview** to test your the event you just configured.

## **Configure an event handler manually**


Add an event handler to a page, component, data resource, or
declarative action within UI Builder so that your user can trigger an
action.


**Before you begin**


Role required: ui_builder_admin


**About this task**


An event handler lets you configure an action, components, data
resource, or declarative action on your page. For example, you can
map an event to your page to add an alert notification when the
page successfully loads or you can add an event handler for a button
component to perform an action when a user clicks it. The event handler
could also be a modal on your page that asks a user to verify that
the user wants to delete the record. For more information, see Manage
actions in UI Builder pages.


**Note:** You can also use Now Assist in UI Builder to configure event
handlers. For more, information, see Configure an event handler with
Now Assist


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a component to your page, such as a button.
For more information about adding components to a page, see Add
and configure components.


5. To add an event handler to your component's event, go to the
configuration panel and select **Events** .
An event handler lets you assign an event to a component. For
example, if you add a button component to your page, you want
it to perform an action when a user clicks it.


6. To start the process of assigning an event to a component select **Add**
**event mapping** .


Some components, such as the button component, only have one
event mapping. Other components can have many events.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-523-1.png)


7. Select an event mapping that you want to configure from the list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-524-1.png)


8. From the Event handler preview screen, select an action that you
want assigned to the component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-525-1.png)


9. Select **Continue** .


10. Select the handler you want to trigger from the event selected in the
earlier step.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-526-1.png)

11. Select **Continue** .


12. Configure the payload for the event.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-527-1.png)


13. Select **Add** .


14. Select **Save** .


15. Test the event by selecting **Preview** in the header and trigger the
action.


**Result**


The configured event handler displays in the events tab of the
configuration panel.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-528-1.png)

## **Configure an event handler with Now Assist**


Use Now Assist in UI Builder to configure event handlers. At present, you
can configure link to destination, open or close modal, and view load
requested event handlers using Now Assist in UI Builder.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .


For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a component to your page, such as a button.
For more information about adding components to a page, see Add
and configure components.


5. To add an event handler to your component's event, go to the
configuration panel and select **Events** .
An event handler lets you assign an event to a component. For
example, if you add a button component to your page, you want
it to perform an action when a user clicks it.


6. In the event handler, select **Link to destination** and select **Continue** .


7. In the Configure section, select **Get Started** .


8. In the **Generate configuration with Now Assist** field:


**•** Type the action you want to perform (For example, open
www.servicenow.com) or select an option from the dynamic
prompts.


**•** You can reference data from page context.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-530-1.png)


9. Select the right arrow icon.
The configurations are set.


10. You can either reject, or accept and edit the configurations.


11. After you review the changes, select **Add** .


12. Test the event by selecting **Preview** in the header and trigger the
action.


**Result**


The event handler configurations are updated.

## **Bind events to add actions**


After you have created events, you can bind them to actions on your
components, pages, data resources, and declarative actions.


**•** Bind an event to a component


Bind data elements within UI Builder so that you can add event actions
to your components.


**•** Bind an event to a page


Use page event mappings to bind data elements within UI Builder so
that you can add event actions to your page.


**•** Bind an event to a data resource


Assign event handlers within UI Builder to individual data resources on
your page. When a data resource successfully fetches new data, it
executes an event handler to take a user to the next step in a flow.


**•** Bind an event to a declarative action


Bind data elements within UI Builder so that you can add event actions
to a declarative action.


Bind data elements within UI Builder so that you can add event actions to
your components.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Each component has specific events that it binds to. For example,
a button component has only a button-clicked event, while other
components can have multiple events that are associated with them.


Some components do not have an event action that is applied to them.
An example is the heading component. Many components require that
you map an event to your component to make it perform an action,
such as loading data.


To add actions to components, pages, and data resources on your
page, you can add an event handler. A button component that you
add to a page is static. By binding an event action to the button, you
can link it to a web page.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Create or open a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a component that has events to which it can bind to your page,
such as a button.
For more information about adding components to a page, see Add
and configure components.


5. To add an event handler to your component, select the **Events** tab.
For more information on how to add event handlers to your
component, see Manage actions in UI Builder pages.


a. To start the process of setting up an event handler for your
component, click **Add event mapping** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-533-1.png)


b. Select the event mapping that you want to configure from the
list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-534-1.png)


c. Select **Continue** .


d. From the Event handler preview section, select an event handler
to bind to your component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-535-1.png)


e. Select **Continue** .


f. Configure the payload for the event.
You configure each event handler differently, depending on the
action of the event. For example, if you add an event handler for
a button component, you can choose what that button action
performs.


g. Select **Add** .


6. (Optional) If you want a modal to pop up for your event, add the
modal to the page before you bind your event to the component.
A modal is a confirmation pop-up that appears when you click
the component. For example, if you add a button component that
deletes a record, you add a modal to ask the user to confirm that
the user wants to delete the record. For more information, see Add
modal to component.


a. Select the **+** icon in the content tree next to **Modals** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-536-1.png)


b. Choose a modal type such as **Confirm** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-536-2.png)


c. Configure the modal.
You can change the text in the modal, the names of the buttons
in the modal, and the size of the modal screen. You can also
set actions for the modal. When you finish configuring the modal,


close it. Notice that the modal you created sits above the body
of your page structure in the content tree.


7. Bind an event to a button component.
You bind an event to the button to trigger an action. Select the
button component to highlight it again, either in the content tree, or
on the page.


a. Select **+ Add content** in the content tree.


b. Select the **Button** component in the toolbox.


c. Select **None** when asked to choose a preset.


d. In the Configuration pane, click **Events** .


e. Select **Add handler** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-537-1.png)


The button component only has the button-clicked event
associated with it. Other components can have more than one
event.


f. Select an handler that you want assigned to the button.


For example, to add an event handler for the button
component, you could link it to another destination and add
alert notifications. In this example, you can choose **Open or close**
**modal dialog** to make the button open the modal that you
created earlier. In this button scenario, select the Confirm and
destroy modal dialog event handler that you created earlier.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-538-1.png)


g. Select **Continue** .


h. Select a modal from the drop-down.


i. Select **Add** to add the modal event handler to your button
component.


8. Click **Save** .


9. Test the modal by selecting **Preview** .


10. To trigger the modal that you created, click the button on the page.


Use page event mappings to bind data elements within UI Builder so that
you can add event actions to your page.


**Before you begin**


Role required: ui_builder_admin


**About this task**


You can bind an event to a page by using the following types of events:


**•** Page event mappings. Add, remove, or clear alert notifications on your

page.


**•** Variant event mappings. Add, remove, or clear alert notifications on
your page variant.


**•** Dispatched events. Create dispatched events for your page to create
relayed event mappings that model events after a parent event
handler. Select a target parent event handler to model the payload
fields after it.


**•** Handled events. A handled event is an event that is exposed and
available for use by other users. After you create a handled event, it
is available under Page event mappings for other users to use. You
can also set up payload fields that you create manually or choose a
template for your handled event, such as an open or close a modal
dialog.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information.


3. Open or create a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Highlight the page body in the content tree.


The body is the top-level line of the content tree. When you highlight
the whole page, you can add page-level events.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-540-1.png)


5. In the configuration panel, select the **Events** tab.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-541-1.png)


6. Add an event handler in one of the following ways.

|To add this event handler|Do this|
|---|---|
|Page event mappings|Page ready source event:<br>a. Select**Add event handler**.<br>b. To add, remove, or clear<br>alert notifications from the<br>page, choose an event<br>handler from Page-level<br>event handlers. You can|


|To add this event handler|Do this|
|---|---|
||add, remove, or clear alert<br>notifications on your page.<br>c. To add the event handler to<br>your page, select**Add**.<br>Page property changed source<br>event:<br>a. Select**Add a new event**<br>**handler**.<br>b. Choose an event handler<br>from Page-level event<br>handlers. You can add,<br>remove, or clear alert<br>notifications on your page.<br>You can also choose**Set**<br>**loading state** to show the<br>word**Loading** on your page<br>so users can see that the<br>page is loading. You can<br>also select**Update client**<br>**state parameter** to change<br>the client state name.<br>c. To add the event handler to<br>your page, click**Add**.|
|Variant event mappings|**Variant event mappings**<br>You must have a variant page<br>to perform a variant event<br>mapping. The Variant event<br>mappings that are available<br>depend on the variant page. If<br>the variant page has a list, you<br>add event handlers for things<br>like Row clicked, Nav item,<br>and so on. When the variant<br>has a Viewport, you may have|


|To add this event handler|Do this|
|---|---|
||different event handlers to set<br>up.<br>a. Select**Add event mappings**.<br>For example, you can add a<br>new event handler for**Row**<br>**clicked**.<br>b. Select an event handler<br>from the list of available<br>Inherited event handlers or<br>local event handlers like the<br>UXR App Shell Data Source.<br>c. To add the event handler to<br>your variant, select**Add**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-543-1.png)


|To add this event handler|Do this|
|---|---|
||**•** These event mappings<br>are in the variant record<br>that are found in the<br>`sys_ux_screen` table.<br>**•** The source events for these<br>event mappings are any<br>dispatched events that are<br>defined for your page.<br>**•** The available handlers<br>for these event mappings<br>are canvas-level events,<br>the UXR App Shell Data<br>Source, and operations from<br>inherited data resources.<br>**•** These event mappings are<br>used as relays so that events<br>that are dispatched from<br>components on your page<br>are relayed up to the user<br>session handlers.<br>**•** These mappings are<br>automatically created on<br>a page save when<br>you have mapped a<br>component's dispatched<br>event to another event.<br>For example, when you<br>map a Button clicked event<br>to the Link to destination<br>event, the event creates a<br>dispatched relay event and<br>a variant event mapping<br>after you save the page.|
|Dispatched events|a. Select**Dispatched events**.<br>b. Select<br>.|


|To add this event handler|Do this|
|---|---|
||c. In the**Add an event** screen,<br>do the following actions:<br>**•** Type a label for your<br>event.<br>**•** Select a target parent<br>event handler.<br>d. To add the event handler<br>to your dispatched events,<br>select**Add**.<br>e. The new event handler<br>that you created appears<br>in**Dispatched events**. The<br>following example shows|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-545-1.png)


|To add this event handler|Do this|
|---|---|
||how to add a Link to<br>destination event handler.<br>**•**<br>These events are in the<br>[sys_ux_event] table. The<br>page definition record<br>contains references to the<br>[sys_ux_event] record.<br>**•**<br>These events serve as source<br>events for variant event<br>mappings.<br>**•**<br>To create new dispatched<br>events for your page,<br>select<br>. Configure<br>the event label to auto-<br>populate the event name<br>and payload fields for your<br>new`sys_ux_event`.<br>**•**|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-546-1.png)


|To add this event handler|Do this|
|---|---|
||These events are often<br>used to create relay event<br>mappings. You can select a<br>Target parent event handler<br>to model the payload fields<br>after the selected event.<br>You can also manually<br>create payload fields for<br>your dispatched event.|
|Handled events|**•**<br>These events are saved<br>in the [sys_ux_event] table.<br>The page definition record<br>contains references to the<br>[sys_ux_event] record.<br>**•**<br>These events serve as source<br>events for Page event<br>mappings.<br>**•**<br>To create new dispatched<br>events for your page, select<br>. These events are<br>not modeled after parent<br>event handlers. Payload<br>fields for handled events are<br>created manually. To use an<br>existing handler's payload<br>fields as a template, select a<br>template and edit the fields<br>as necessary.|


7. Select **Save** .


8. To preview your page and test the data resource event that you set


up, select .


Assign event handlers within UI Builder to individual data resources on
your page. When a data resource successfully fetches new data, it
executes an event handler to take a user to the next step in a flow.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Bind an event to a data resource, to perform data-related actions on
your page. For example, you can add a button to reload data to a page
if it doesn't load the first time. You can also set up a data resource event
to reload data behind the scenes of your page.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Create or open a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. (Optional) If you do not have any components on your page, add
one to your page.
For more information, see Add and configure components.


5. Add a data resource to your page.
For more information, see Add and configure data resources to a

page.


6. Select a data resource instance.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-549-1.png)


7. To add an event handler to your data resource, select the **Events** tab
in the configuration panel of the data resource.


You can add event handlers to your data resource to handle actions
for Operation Initiated, Operation Succeeded, and Operation Failed.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-549-2.png)


8. Select **Add event mapping** .


9. Select an event from the list.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-550-1.png)


10. Select **Continue** .


11. Select an event handler from the list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-551-1.png)


12. Select **Continue** .


13. Fill in the required information for the event handler.
The configuration varies depending on which event handler is
selected.


14. Select **Add** .


15. Select **Save** .


16. To preview your page and test the data resource event that you set


up, select in the UI Builder header.


**•** Link an event to another page


Add a link to the destination event handler within UI Builder so that
an event action can open another page. You can also configure the
event handler to follow the App Route to the desired page.


Add a link to the destination event handler within UI Builder so that an
event action can open another page. You can also configure the event
handler to follow the App Route to the desired page.


**Before you begin**


You must have a workspace page that contains a component that is
intended to open another page when a user clicks it. The dashboard
overview is an example of such a component. Components such as **Link**
**to Destination** do not support the link to destination event handle. The
component link property takes priority over the link to destination event
handler.


Role required: ui_builder_admin


**About this task**


To configure an event action to open another page, you must
know what page you want to open, what the required and optional
parameters are for that page, and what payload values to set on the
event handler to pass the required parameters to the destination page.


**Tip:** You may be able to find examples of both the components
that you want to link from and the destination pages that you
want to link to in the Base Agent Workspace Experience. This Next
Experience is provided in the base system. If you create a page
from a page template, you should only copy the contents of the
template. Do not reference it. For more information about the
difference between copying and referencing a page template, see
Create a page from a template.


**Procedure**


1. Open your experience in UI Builder.


2. (Optional) If the destination page doesn't exist in your experience,
create one.


For information about creating pages, see Create a page in
UI Builder. Make sure that you set the required and optional
parameters for the page so that you can use it as a destination.
If a particular component in the page is a destination, you must
include that component. You also must configure the properties
on the component to consume the page parameters with
`@context.props.<parameter-name>` values.


You might consider creating the page from a page template. The
Base Agent Workspace Experience has several page templates that
are already configured to be destinations for other components. If
you create a destination page from a template, the components are
already configured with the correct properties. Any necessary state
parameters or client scripts are also copied over. You have to add
the page parameters. You can copy these parameters from the UX
App Routes related list on the Agent app config [sys_ux_app_config]
record of the experience that contains the page templates.


To make sure that the pages that you are creating work reliably as
destinations in your experience, your experience must have the same
app shell UI as the experience with the page templates.


3. Switch to the page that you want to link to the destination page.


4. Navigate to the relevant component and select it.


5. Select the **Events** tab.


6. Select **+ Add event mapping** .


7. Select the event you want to use.


8. Select **+ Add event handler** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-554-1.png)


9. In the Inherited event handlers section, select **Link to destination** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-555-1.png)

10. Click **Select destination** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-556-1.png)


11. Expand **Pages** and select the page in the experience that you want
to link to.
Fields appear for each of the parameters on the destination page
that the route leads to. Required parameters are marked with an
asterisk (*).


12. Complete each required parameter field and the applicable
parameter fields with an appropriate `@payload.*` value.
If the developers of your component included default payload
values in your event, you can select one through autocompletion. As
shown in the following example, the payload value may not match
the parameter name.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-557-1.png)


**Note:** You have the option to link to an External URL instead of
specifying an **App route** .


If no default values are provided, or you can't determine which
values are correct for some fields, refer to the configuration and API
[documentation for the component in the ServiceNow® Developer](https://developer.servicenow.com/)
[Site. If you still can't find the necessary](https://developer.servicenow.com/) `@payload.*` values, contact
Customer Service and Support.


**Tip:** If you create your linking component by creating a page
from a Base Agent Workspace page template, the component
contains Link to destination Relay event handlers. These event
handlers do not work. However, they contain the applicable
`@payload.*` values for the parameters.


**Example: Configuring the event handlers for an Analytics Q&A**
**component**


Let's say that you want to take a new Next Experience and add a
page with an Analytics Q&A component. First, you create the page from
the Analytics Center page template that is provided in the Base Agent
Workspace experience. Next, you create a target page for the first of the
three events in Analytics Q&A and then you configure an event handler
for that event.


By navigating to **Now Experiences Framework > Experiences**, you see
the Test experience UX application. Because it uses the same Agent
Workspace App Shell UI as the Base Agent Workspace, you can use the
page templates from the Base Agent Workspace.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-558-1.png)


You next select the Test workspace admin panel, find an UX App
Configuration record with no UX app routes or pages, and then click
**Open** .


As the example shows, in the UI Builder, you have created a page
named Analytics Center that is based on the Analytics Center page
template from the Base Agent Workspace. Next, you select the option to
copy only the contents of the page template.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-559-1.png)


You select the Analytics Q&A 1 component and open the **Events** tab.
From here, you can open the **Link to destination Relay** event handler for
the **Report Visualization Clicked** event. When a question in Analytics Q&A
returns a report, you can trigger this event by clicking a value in the
report. When you click a value, you also see a list of the records that
contribute to this value. In the **Route** field, you see that the destination
is expected to be a page that is based on the Simple List page
template. You also see the parameters of the page that the `@payload.*`
values correspond to, and that the **Title** field can be populated with
`@payload.listTitle` .


**Parameters of suggested Simple List destination page and**
**corresponding payloads**


**Parameter** **@payload.* value**

|table (required)|@payload.table|
|---|---|
|listTitle|@payload.listTitle|
|query|@payload.query|
|disableInlineEditing|none|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-561-1.png)


Next, you navigate to **Menu > Create page** and create a page that is
based on the Simple List template. Let's say that you name the page
as Record list. You then follow a similar process as when you created
the Analytics Center page. This time, in the last steps of the process, you
would add `table` as a required parameter and `listTitle`, `query`, and
`disableInlineEditing` as optional parameters.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-562-1.png)


Because this page already contains a List component, when you open
the **Config** tab for this component, you see that the parameters are
already passed in the `@context.props.*` values.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-563-1.png)


Now, you return to the Analytics Center page. In the **Report Visualization**
**Clicked** event, you add a new event handler. Next, you select the
Record list page that you created and add the `@payload.*` values in
the **table**, **listTitle**, and **query** fields, following the information that you got
from the **Link to destination Relay** event handler. Predictive typing helps
you to fill in these fields.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-564-1.png)


After you click **OK** and add `@payload.listTitle` as the **Title**, the event
handler is done. You can now delete the **Link to destination Relay** event
handler for this event.


The following example shows an Analytics Center page. On this page,
you can enter a query for Incidents by Priority and get a report as a result.
Also, by clicking a column, you trigger a **Report Visualization Clicked**
event. The event handler enables you to see a simple list of the incidents
in the report.


Triggering the configured Report Visualization Clicked event

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-565-1.png)


Bind data elements within UI Builder so that you can add event actions to
a declarative action.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Bind a handled event to a component so that an action is performed
when a user selects the component.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Add a component to your page that can have a declarative action,
such as an action bar or related list.
For more information, see Add and configure components.


5. To create a declarative action definition in a table in the ServiceNow
AI Platform®, navigate to **Workspace Experience > Actions &**
**Components > List actions** .


Choose a table where you want the declarative action to be
available in. For example, you could create a Complete my work
action in an incident table or you could use an existing declarative
action definition record.


Platform declarative action definition record

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-566-1.png)


6. Select the **Active** check box, and then save or update the record.


7. Return to the UI Builder.


8. To invoke a handled event for the declarative action, go to
the Configure panel and click **Configure declarative action event**
**mapping** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-567-1.png)


9. Choose the declarative action that you created earlier.
To continue with the example in step 5, the declarative action could
be something like **Complete my work** .


10. To define what the declarative action does on your page, click **+**
**Add event handler** .


a. Give the event handler a name.
The name should describe what action you want the event
handler to perform.


b. (Optional) Provide a description of the event handler.


c. Choose the handled event that you want to invoke.


d. (Optional) Add payload values for your event handler.


e. Select **Save** .


11. Select **Done** .


12. Select **Save**, and then select .


13. Test the declarative action on your page by clicking **Complete my**
**work** to see if it works.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-568-1.png)

## **Disable component preset event mappings**


You can disable event mappings that are automatically created by a
component preset.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page.


For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select a component with a component preset configured.


5. Select the **Events** tab in the configuration panel.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-569-1.png)


6. Select the event that you want to disable.


7. Select **Disable** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-570-1.png)


8. Select **Done** .


**Result**


The component preset event shows **Disabled** in the **Events** tab of the
configuration panel.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-571-1.png)

## **Delete an event handler**


Delete an event handler that you no longer need in UI Builder.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select a component with a preset configured.


5. Select the **Events** tab in the configuration panel.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-572-1.png)


6. Select the event handler that you want to delete.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-573-1.png)

7. Select **Delete** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-574-1.png)


8. Select **Delete** in the confirmation modal.


9. The event handler is removed from the associated event mapping.


If you would like to delete the event mapping, see Delete an event
mapping.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-575-1.png)

## **Delete an event mapping**


Delete an event mapping that you no longer need in UI Builder.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select a component with a preset configured.


5. Select the **Events** tab in the configuration panel.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-576-1.png)


6. Select the delete all icon ( ) next to the event you want to delete.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-577-1.png)


7. The event mapping is removed from the associated component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-578-1.png)

## **Add events to track components with unsaved** **changes**


Locate dirty state components through event configuration.


**Before you begin**


Role required: ui_builder_admin


**About this task**


You can add the **Screen status changed to dirty** event to check which
components have unsaved changes. This avoids having to manually


inspect advanced properties on events for each individual component.
Once added, the event remains available in the configuration panel for
direct access.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. In the content tree, select **+ Add content** to add a component.


5. Select a component from the toolbox and select **Add** .
For example, select a **Button** .


6. Add an event to the component.


a. Select the **Events** tab in the configuration panel.


b. Under **Button clicked**, select **Add handler** .


c. Under **Choose a handler**, enter `isDirty` (or `dirty` ) into the
search bar.


d. Select the **Screen status changed to dirty** event and select
**Continue** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-580-1.png)


e. Select the **Screen is dirty** check box to mark the property as
`true` .


f. Select **Add** .
The dirty state event now appears in the configuration panel,
enabling you to quickly check the `isDirty` property and determine
if the component has unsaved changes without adding additional
events.

## Manage the visual style of UI Builder experiences


Themes enable you to change the visual style of your UI Builder
experiences so that they express the look and feel of your brand


**Getting started with themes**


By default, the Polaris theme is applied to UI Builder experiences. For more
[information, see Working with themes in Next Experience.](https://www.servicenow.com/docs/csh?topicname=next-experience-theming&version=zurich&pubname=zurich-platform-user-interface)


**Create a new theme with Theme Builder**


Theme Builder enables you to create, edit, manage, and apply Next
Experience themes using a friendly visual interface. For more information,
[see Configuring Next Experience with Theme Builder.](https://www.servicenow.com/docs/csh?topicname=configuring-next-experience-with-theme-builder&version=zurich&pubname=zurich-platform-user-interface)


**Create a custom theme**


If you are an admin user comfortable working in style records and
JSON code, you can create a custom theme to override the default
Polaris style. This option gives you the most control over typefaces, colors,
and images (including the banner and logo) in a theme. For more
[information, see Configuring Next Experience themes and preferences.](https://www.servicenow.com/docs/csh?topicname=config-next-experience-themes-prefs&version=zurich&pubname=zurich-platform-user-interface)


**Working with dark theme**


[If you are interested in dark theme, see Working with the dark theme.](https://www.servicenow.com/docs/csh?topicname=tb-working-in-dark-theme&version=zurich&pubname=zurich-platform-user-interface)


**Create custom style classes and rules**


Use style classes rules in UI Builder to apply custom visual styling to UI
elements by referencing CSS classes, see Create custom style classes and
rules.


**•** View experience theme


View the theme applied to your experience. The theme sets the visual
style of the experience and provides a consistent look and feel across
all pages.


**•** Create custom style classes and rules


Use style classes rules in UI Builder to apply custom visual styling to UI
elements by referencing CSS classes.

## **View experience theme**


View the theme applied to your experience. The theme sets the visual
style of the experience and provides a consistent look and feel across all

pages.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Select **Settings** in the UI Builder header.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-582-1.png)


4. Scroll to the **Branding and theming** section and note what is listed in
**Themes** .
By default, the Polaris theme is applied to UI Builder experiences.


**What to do next**


If you want to customize the theme, there are two options:


**• Theme Builder** enables you to create, edit, manage, and apply
Next Experience themes using a friendly visual interface. For more
[information, see Configuring Next Experience with Theme Builder.](https://www.servicenow.com/docs/csh?topicname=configuring-next-experience-with-theme-builder&version=zurich&pubname=zurich-platform-user-interface)


**•** If you are an admin user comfortable working in style records and JSON
code, you can create a custom theme to override the default Polaris
style. This option gives you the most control over typefaces, colors,
and images (including the banner and logo) in a theme. For more
[information, see Configuring Next Experience themes and preferences.](https://www.servicenow.com/docs/csh?topicname=config-next-experience-themes-prefs&version=zurich&pubname=zurich-platform-user-interface)

## **Create custom style classes and rules**


Use style classes rules in UI Builder to apply custom visual styling to UI
elements by referencing CSS classes.


**Before you begin**


Role required: admin


**About this task**


Control the appearance of fields, containers, buttons, and other
interface components without writing inline styles making the UI cleaner,
more consistent, and easier to maintain. All style classes and rules can
be applied to any container or component on the page. For more
[information about CSS styles, see the ServiceNow Developer site and the](https://developer.servicenow.com/dev.do#!/guides/yokohama/now-platform/next-experience-guide/now-experience-css)
[ServiceNow Community site.](https://www.servicenow.com/community/developer-blog/the-ultimate-service-portal-css-guide/ba-p/2290168)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. Add a component to your page.


5. Select the **Styles** tab in the configuration panel.


6. Select the **...** icon next to the **Style class** field.


The **Page classes and rules** pop up will appear.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-584-1.png)


7. (Optional) Select **+ Add class** .


a. Enter a name in the **Style class name** field.


b. Provide the CSS style you would like to apply to the component.


c. Select **Apply** .


8. (Optional) Select **+ Add rule** .


a. Enter a name in the **Style rule name** field.


b. Provide the CSS rule you would like to apply to the component.


c. Select **Apply** .


9. Close the **Page classes and rules** pop up.


10. Select the **Style class** field.


11. Select a style class or style rule from the list.


12. Select **Save** .


13. Select **Preview** to test the applied style class or style rule.

## Collaborate with other UI Builder developers


UI Builder provides real-time collaboration tools and user presence
indicators for more efficient and intuitive UI development.


UI Builder lets you see who is online and working on the same page in an
experience.


The avatars of other developers appear in the UI Builder header next to
the undo button. A dot on the avatar of the user represents online status.


**•** Green dot if the user is currently working on the page


**•** No dot if the user is not logged in

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-585-1.png)


A banner will appear asking you to reload the page to view the latest
version if changes are made by other users while you are editing a page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-586-1.png)


If you have made changes at the same time as another user you will
be prompted to **Overwrite and save** your changes to proceed with
previewing the page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-586-2.png)


**Find and compare page changes**


Track and compare changes between different versions of a page when
collaborating with other page builders.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open the experience that contains the page where you want to
compare changes.


3. Select the page with the changes you want to compare.


4. Select the menu icon.


5. Select **Compare versions** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-588-1.png)

The **Version comparison** drawer opens.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-589-1.png)


6. Review changes by selecting an item that displays one of the
following:


**•** Added


**•** Modified


**•** Moved


**•** Deleted

## Find and fix issues in UI Builder


UI Builder can help identify common configuration issues and guidance
on how to fix them.


UI Builder can help you find and fix issues by checking your experience for
missing configurations, errors, and accessibility standards. The list of issues
can be found within the experience view of UI Builder under the **Find and**
**fix issues** section.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-590-1.png)


Find and fix issues list

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-591-1.png)


You can also find UI Builder issues in the header of the page builder
next to the **Save** button. The button auto updates as it finds errors and
recommendations for the content on your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-592-1.png)


To find more information, select the builder icon to view the list of
recommendations made by UI Builder. Each error and warning will list the
component name that contains the issue.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-593-1.png)


**Find and fix issues in UI Builder**


Find and fix issues found in your UI Builder experience.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open the experience you want to check for issues by selecting
**Experiences** .


3. Select **See more** under the **Find and fix issues** section.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-594-1.png)


4. Fix the issues found in your experience by selecting button under the
**Reference** section.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-595-1.png)


A new tab will open to the page with the issue.


5. Select the error button in the header to get a brief description of the
issue and which component contains the issue.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-596-1.png)


The component name will be listed in the error or warning.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-597-1.png)


6. Select the component with the issue and follow the instructions listed
in the warning or error text.


7. Select **Save** .

## Getting help with the Now Assist panel in UI Builder


Get Now Assist's AI-driven guidance while working in UI Builder.


You can configure Conversational Help in the Now Assist panel to
be accessible from any page within UI Builder. Conversational Help
uses generative AI to provide instant support from anywhere in your
experience, enabling you to ask questions and get quick answers without
disrupting your current activity.


Conversational Help answers questions based on product
documentation, but cannot provide guidance specific to what you've
configured in your instance.


**Note:** You must install the Now Assist for Creator plugin in the
Now Assist Admin console to use the Now Assist panel. For more
[information, see Now Assist Admin console](https://www.servicenow.com/docs/csh?topicname=configuring-now-assist&version=zurich&pubname=zurich-intelligent-experiences)


**What to ask**


Ask questions in the Now Assist panel to discover new features and learn
how to complete specific tasks. For example:


**•**
```
 Can I configure side navigation?

```

**•** `How do I bind dynamic data to a repeater?`


**•**
```
 Where can I find best practices and design considerations
 when using Next Experience Components on my page?

```

**•** `How do I create a reusable page template?`


[For more information on the Now Assist panel, see Now Assist panel.](https://www.servicenow.com/docs/csh?topicname=now-assist-panel-overview&version=zurich&pubname=zurich-intelligent-experiences)


**Get help with the Now Assist panel in UI Builder**


Ask questions and get quick answers without leaving UI Builder.


**Before you begin**


**•** Role required: ui_builder_admin


**•** The Now Assist for Creator plugin is activated


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. In the upper right, select the Now Assist icon to open the
Now Assist panel.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-599-1.png)


**Tip:** You can select the pin icon to keep the panel
visible while you work.


5. Enter your question in the text field.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-599-2.png)


6. Press the Enter key or select the **Send** button.
Conversational Help uses generative AI to provide immediate
answers to your questions.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-600-1.png)


7. (Optional) Continue the conversation with follow-up questions as
needed.


## **Advanced UI Builder**


UI Builder can be used by application developers with a variety of
skill levels. We recommend developers with a high level of experience,
sometimes referred to as pro-coders, perform the procedures in this
section.


**•** Configure components and repeaters (advanced feature)


You can add and configure components as you build pages in UI
Builder. You can also use repeaters to repeat components or multiple
components with results from a data resource.


**•** Dynamically expose data in UI Builder pages (advanced feature)


Sync data between ServiceNow tables and data with the pages you
build with UI Builder. Pages display synced data in real time and update
data/tables when a user inputs information.


**•** Edit code with the Now Code Editor (advanced feature)


Now Code Editor is a rich-text editor like interface that supports
Cascading Style Sheets (CSS), Hypertext Markup Language (HTML),
JavaScript, Extensible Markup Language (XML), and JavaScript Object
Notation (JSON). Use Now Code Editor to modify UI configuration, data
resource configuration, styles, events, client-side and server-side scripts
in Next Experience UI Builder components.

## Configure components and repeaters (advanced feature)


You can add and configure components as you build pages in UI
Builder. You can also use repeaters to repeat components or multiple
components with results from a data resource.


**•** Add and configure components


Learn how to add components to your page in UI Builder. A page is
built by adding components.


**•** Add repeaters to components


In UI Builder, use repeaters to repeat one or more components with
results from a data resource.


**•** Optimize page loading performance (Advanced Feature)


Performance settings enhances leading speeds and user engagement
by displaying high-priority content first, making key components
interactive sooner for a faster perceived performance.

## **Add and configure components**


Learn how to add components to your page in UI Builder. A page is built
by adding components.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Components are the building blocks used to create custom pages
in UI Builder. Learn how to add a component to a page. After you
add a component to a page, you must configure the component.
[For more information about configuring components, see Component](https://developer.servicenow.com/dev.do#!/reference/next-experience/components?&query=&order_by=nameAsc&limit=120&offset=0&categories[]=uib_component&categories[]=uib_macroponent-component&categories[]=uib_facades)
[documentation on the ServiceNow Developer Site.](https://developer.servicenow.com/dev.do#!/reference/next-experience/components?&query=&order_by=nameAsc&limit=120&offset=0&categories[]=uib_component&categories[]=uib_macroponent-component&categories[]=uib_facades)


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open or create a page.
If you open an existing page, make sure you are in the same
scope as the original page. If not, change the scope before you
start editing the page. Application scoping protects applications
by identifying and restricting access to application files and data.
Administrators set the scope to specify what parts of an application
are accessible to other applications. Application scope protects


data and application files. See Learn about security and roles for
more information about application scope.


4. Select an existing container or create a column layout.
See Organize components in UI Builder pages for more information.


5. Add components to your page.
UI Builder comes with a library of components to choose from. You
add components as the building blocks of your page. For example,
you can add a heading, data visualizations, and so on. The following
table shows you the different ways you can add a component to a

page.

|To add a component|Do the following|
|---|---|
|Directly from your page|From your page, select**+**<br>and choose a component<br>from the toolbox. You can<br>search for a component<br>or scroll through the list.|
|Floating menu above page|Select the floating menu above<br>your component.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-603-1.png)


|To add a component|Do the following|
|---|---|
||**•** Select**Add before** or**Add**<br>**after**.<br>**•** Choose a component from<br>the toolbox.|
|Content tree|You can add a component<br>from the content tree in the<br>following two ways.<br>**•** Select**+Add content**<br>beneath a container in the<br>content tree. Then choose<br>a component from the<br>toolbox.<br>**•** Move your mouse device<br>over a container in the<br>content tree, select the<br>**Menu** icon, and select**Add**<br>**component**. Then choose|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-604-1.png)


|To add a component|Do the following|
|---|---|
||a component from the<br>toolbox.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-605-1.png)


6. Now configure the properties of the components that you just
added.
Configuring components means to customize them to your needs.
[For more information about configuring components, see Next](https://developer.servicenow.com/dev.do#!/reference/now-experience/rome/components)
[Experience Components.](https://developer.servicenow.com/dev.do#!/reference/now-experience/rome/components)


a. Select the component that you want to configure.


b. Select the **Configure** tab from the configuration panel in UI
Builder.


c. Customize the component properties for the component.
For example, you could add a name for a button component.
Some components, like data visualizations, require a data source
before you can configure the properties. Each component has
different configuration properties based on the requirements
and options for each component. For example, the **Button**
component configuration is simple, while a **List** component
requires more configuration.


d. For components with configurable JSON properties, you can use
UI Builder's low-code JSON editor to edit component properties
without needing to edit JSON code.


The JSON editor UI displays all available properties, even
properties not defined in the dummy data or defined values.
You can update properties or add your own custom properties
within the JSON editor. For more information about configuring
components, see Edit code with the Now Code Editor
(advanced feature).


**Note:** The low-code JSON editor is only available to
properties that have a schema and whose JSON input
matches said schema.


The low-code JSON editor supports simple objects, simple array
properties, complex arrays, arrays of objects, and partially
supports complex objects. For complex arrays, you can add,
delete, or move the position of array items. You can also select
**Hide unset items** to hide objects with empty or null values for a
simplified editing experience.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-607-1.png)


e. When working with a container component, you can edit some
styles by using the floating panels.


Select the **Menu** icon to view a menu.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-608-1.png)


Select the **Layout**, **Sizing**, or **Spacing** option to open a floating
panel with the most common options displayed. Drag the
floating panel to another location as needed. Only one floating
panel can be open at a time.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-608-2.png)


[For more information about configuring components, see Next](https://developer.servicenow.com/dev.do#!/reference/now-experience/rome/components)
[Experience Components.](https://developer.servicenow.com/dev.do#!/reference/now-experience/rome/components)


7. (Optional) Select the **Events** tab to add an event handler to your
component.
Add an event handler to add actions to the components on your
page. For example, a button component is static and doesn’t do
anything until you bind an event action to it, such as saving a record.
Some components don’t have an event action applied to them,
such as a heading component. But many components require you
to map an event to your component to actually make it perform an
action. See Bind an event to a component for more information on
how to add event handlers to your component.


8. (Optional) You can override any styles for a component by adding
CSS styling under the **Styles** tab.
For more information, see Change the default appearance of
components.


**Note:** Style changes only affect a single component at a
time. To change the visual style of all the components in your
experience, you must apply a theme to your experience. For
more information, see Manage the visual style of UI Builder
experiences.


9. (Optional) Add additional containers to your page to display your
components in an organized way.
For example, one container could have a heading component.
Another container below it could include a list component, a button
component, and so on.


a. Select the **+** at the top of your container to add a container
component before the existing component and select the **+** at
the bottom of a component to insert a container component
after it.


b. Drag a container component from the Components list to
your existing container on the page; Hold over the top line of
the container to insert the new container before the existing
container or over the bottom line of the existing container to add
it after.


10. (Optional) Add more components to your page by selecting the **+** on
the top or bottom of the components on the page (the **+** changes to
**+ Add** ).

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-610-1.png)


a. Select the **+** at the top of your component to add a component
before the existing component or select the **+** at the bottom of a
component to insert a component after it.


b. Drag a component from the component list to insert the
component before or after an existing component.


11. (Optional) To make a modal appear when you select a component
such as a button, you must add the modal to the component first.
A modal is a confirmation pop-up that appears when you select
the component. For example, if you add a button component that
deletes a record, you add a modal to ask the user to confirm they
want to delete the record. See Create modals in UI Builder for more

information.


12. Select **Save** often on your page as you work.


13. View and test your page by selecting the **Preview** button.


**What to do next**


You have added and configured components on your page. See
Dynamically expose data in UI Builder pages (advanced feature) for
more information. A data resource in UI Builder is the data that a
page fetches to display content in components. Components use data
resources as a way to reuse data and configurations across different
experiences, and make the components dynamic on a page.


**Supported functions in the UI Builder component formula editor**


Learn about the various functions supported in the UI Builder component
formula editor.


The following table lists the functions you can use in the UI Builder
component formula editor. For more information about the component
formula editor, see Customize UI Builder pages using components.


**Operators available for condition builders**


**Example**

**query**


**Example**
**Operator label**
**condition**


**Example**
**output**


**Equivalent**

**query**
**operator**


|All empty|[Short<br>description]<br>[ALL_EMPTY]|ALL_EMPTY|short_descrip<br>tionALL_EMP<br>TY|All records in<br>which there<br>is no value in<br>the Short<br>description<br>field.|
|---|---|---|---|---|
|All equal|[Short<br>description]<br>[ALL_EQ]<br>[Network<br>storage<br>unavailable]|ALL_EQ|short_descrip<br>tion=network<br>storage<br>unavailable|All records in<br>which the<br>value for the<br>**Short**<br>**description**<br>field is equal<br>to "Network<br>storage is<br>unavailable."|
|All greater<br>than|[Impact]<br>[ALL_GT][2 -<br>Medium]|>|impact>2|All records in<br>which the<br>**Impact** field<br>has a value<br>of**3 - Low**|
|All greater<br>than or<br>equal|[Impact]<br>[ALL_GTE][2 -<br>Medium]|>=|impact>=2|All records in<br>which the<br>**Impact** field<br>has a value<br>of**2 -**|


**Example**
**Operator label**
**condition**


**Equivalent**

**query**
**operator**


**Example**

**query**


**Example**
**output**


|Col1|Col2|Col3|Col4|Medium or 3<br>- Low.|
|---|---|---|---|---|
|All less than|[Reassignme<br>nt count]<br>[ALL_LT][2]|<|reassignmen<br>t_count<2|All records in<br>which the<br>value in the<br>**Reassignme**<br>**nt count** field<br>is any<br>number less<br>than (but<br>not equal to)<br>**2**.|
|All less than<br>or equal|[Reassignme<br>nt count]<br>[ALL_LTE][2]|<=|reassignmen<br>t_count<=2|All records in<br>which the<br>value in the<br>**Reassignme**<br>**nt count** field<br>is one of the<br>following:<br>**•** a number<br>less than 2<br>**•** 2|
|All not equal<br>to|[Impact]<br>[ALL_NEQ][1<br>- High]|!=|impact!=1|All records in<br>which the<br>value in the<br>**Impact** field<br>is anything<br>but**1 - High**.|
|All not<br>empty|[Impact]<br>[ALL_NOTEM<br>PTY]|ALL_NOTEMP<br>TY|impactALL_<br>NOTEMPTY|All records in<br>which the<br>**Impact** field|


**Example**

**query**


**Example**
**Operator label**
**condition**


**Equivalent**

**query**
**operator**


**Example**
**output**


|Col1|Col2|Col3|Col4|has any<br>value.|
|---|---|---|---|---|
|All not one<br>of|[Impact]<br>[ALL_NOTON<br>EOF][1 -<br>High, 2 -<br>Medium]|ALL_NOTONE<br>OF|impactALL_<br>NOTONEOF1,<br>2|All records in<br>which the<br>**Impact** field<br>is populated<br>by anything<br>except the<br>following<br>values:<br>**• 1 - High**<br>**• 2 -**<br>**Medium**|
|All one of|[Impact]<br>[ALL_ONEOF]<br>[1 - High, 2 -<br>Medium]|ALL_ONEOF|impactALL_<br>ONEOF1,2|All records in<br>which the<br>**Impact** field<br>is populated<br>by one of<br>the following<br>values:<br>**• 1 - High**<br>**• 2 -**<br>**Medium**|
|Any empty|[Short<br>description]<br>[ANY_EMPTY]|ANY_EMPTY|short_descrip<br>tionANY_EM<br>PTY|Any record<br>in which<br>there is no<br>value in the<br>**Short**<br>**description**<br>field.|


|Operator label|Example condition|Equivalent query operator|Example query|Example output|
|---|---|---|---|---|
|Any equal|[Short<br>description]<br>[ANY_EQ]<br>[Network<br>storage<br>unavailable]|ANY_EQ|short_descrip<br>tion=network<br>storage<br>unavailable|Any record<br>in which the<br>value for the<br>**Short**<br>**description**<br>field is equal<br>to "Network<br>storage is<br>unavailable."|
|Any greater<br>than|[Impact]<br>[ANY_GT][2 -<br>Medium]|ANY_GT|impactANY_<br>GT2|Any records<br>in which the<br>**Impact** field<br>has a value<br>of**3 - Low**|
|Any greater<br>than or<br>equal|[Impact]<br>[ANY_GTE][2<br>- Medium]|ANY_GTE|impactANY_<br>GTE2|Any record<br>in which the<br>**Impact** field<br>has a value<br>of**2 -**<br>**Medium** or**3**<br>**- Low**.|
|Any less than|[Reassignme<br>nt count]<br>[ANY_LT][2]|ANY_LT|reassignmen<br>t_countANY_<br>LT2|Any record<br>in which the<br>value in the<br>**Reassignme**<br>**nt count** field<br>is any<br>number less<br>than (but<br>not equal to)<br>**2**.|
|Any less than<br>or equal|[Reassignme<br>nt count]<br>[ANY_LTE][2]|ANY_LTE|reassignmen<br>t_countANY_<br>LTE2|Any record<br>in which the<br>value in the<br>**Reassignme**|


|Operator label|Example condition|Equivalent query operator|Example query|Example output nt count field|
|---|---|---|---|---|
|||||**nt count** field<br>is one of the<br>following:<br>**•** a number<br>less than 2<br>**•** 2|
|Any not<br>equal|[Impact]<br>[ANY_NEQ][1<br>- High]|ANY_NEQ|impactANY_<br>NEQ1|Any record<br>in which the<br>value in the<br>**Impact** field<br>is anything<br>but**1 - High**.|
|Any not<br>empty|[Impact]<br>[ANY_NOTE<br>MPTY]|ANY_NOTEM<br>PTY|impactANY_<br>NOTEMPTY|Any record<br>in which the<br>**Impact** field<br>has any<br>value.|
|Any not one<br>of|[Impact]<br>[ANY_NOTO<br>NEOF][1 -<br>High, 2 -<br>Medium]|ANY_NOTON<br>EOF|impactANY_<br>NOTONEOF1,<br>2|Any record<br>in which the<br>**Impact** field<br>is populated<br>by anything<br>except the<br>following<br>values:<br>**• 1 - High**<br>**• 2 -**<br>**Medium**|
|Any one of|[Impact]<br>[ANY_ONEO|ANY_ONEOF|impactANY_<br>ONEOF1,2|Any record<br>in which the|


**Example**

**query**


**Example**
**Operator label**
**condition**


**Equivalent**

**query**
**operator**


**Example**
**output**


|Col1|F][1 - High, 2<br>- Medium]|Col3|Col4|Impact field<br>is populated<br>by one of<br>the following<br>values:<br>• 1 - High<br>• 2 -<br>Medium|
|---|---|---|---|---|
|CONCAT|CONCAT(val<br>ue)|CONCAT|CONCAT("W<br>elcome,<br>",@context.s<br>ession.user.fir<br>stName)|Create a<br>new string<br>that<br>combines all<br>supplied<br>strings into<br>one|
|EMPTY|EMPTY(value<br>)|EMPTY|EMPTY(@con<br>text.session.u<br>ser.roles)|Returns true<br>if value is null<br>or undefined|
|IF|IF(if, then,<br>else)|IF|IF(@context.<br>props.bare,"<br>bare<br>page","not<br>bare page")|If condition is<br>true, return<br>the value<br>then. If<br>condition is<br>false, return<br>the value<br>else.|
|LEN|LEN(list)|LEN|LEN([1,2,3])|Returns the<br>number of<br>items in the<br>array|


|Operator label|Example condition|Equivalent query operator|Example query|Example output|
|---|---|---|---|---|
|Pick|PICK(array,<br>field)|Pick|PICK(@conte<br>xt.session.use<br>r.preference<br>s,"name")|Creates a<br>new array<br>where each<br>item is<br>picked from<br>field in each<br>item in the<br>array. If the<br>field does<br>not exist, the<br>item in the<br>new array<br>will be<br>EMPTY|
|Range|RANGE(from,<br>to)|Range|RANGE(1,10)|Creates an<br>array of<br>numbers,<br>starting with<br>from, up to,<br>incrementin<br>g by step|
|Sum|SUM(array)|Sum|SUM([1,2,3])|Starting at 0,<br>add the<br>number<br>value of<br>each item in<br>the array<br>and return<br>the resulting<br>summation|
|Translate|TRANSLATE(t<br>ext)|Translate|TRANSLATE("<br>Welcome<br>back")|Returns the<br>string from<br>the first<br>argument<br>after the<br>characters|


|Operator label|Example condition|Equivalent query operator|Example query|Example output specified in|
|---|---|---|---|---|
|||||specified in<br>the second<br>argument<br>are<br>translated<br>into the<br>characters<br>specified in<br>the third<br>argument.|
|Where<br>empty|[Short<br>description]<br>[WHERE_EMP<br>TY]|WHERE_EMPT<br>Y|short_descrip<br>tionWHERE_E<br>MPTY|Extract<br>records<br>where there<br>is no value in<br>the**Short**<br>**description**<br>field.|
|Where equal|[Short<br>description]<br>[WHERE_EQ]<br>[Network<br>storage<br>unavailable]|WHERE_EQ|short_descrip<br>tionWHERE_E<br>Qnetwork<br>storage<br>unavailable|Extract<br>records<br>where the<br>**Short**<br>**description**<br>field is equal<br>to "Network<br>storage is<br>unavailable."|
|Where<br>greater than|[Impact]<br>[WHERE_GT]<br>[2 - Medium]|WHERE_GT|impactWHER<br>E_GT2|Extract<br>records<br>where the<br>**Impact** field<br>has a value<br>of**3 - Low**|
|Where<br>greater than<br>or equal|[Impact]<br>[WHERE_GTE]<br>[2 - Medium]|WHERE_GTE|impactWHER<br>E_GTE2|Extract<br>records<br>where the<br>**Impact** field|


**Example**

**query**


**Example**
**Operator label**
**condition**


**Example**
**output**


**Equivalent**

**query**
**operator**


|Col1|Col2|Col3|Col4|has a value<br>of 2 -<br>Medium or 3<br>- Low.|
|---|---|---|---|---|
|Where less<br>than|[Reassignme<br>nt count]<br>[WHERE_LT]<br>[2]|WHERE_LT|reassignmen<br>t_countWHE<br>RE_LT2|Extract<br>records<br>where the<br>value in the<br>**Reassignme**<br>**nt count** field<br>is any<br>number less<br>than (but<br>not equal to)<br>**2**.|
|Where less<br>than or<br>equal|[Reassignme<br>nt count]<br>[WHERE_LTE]<br>[2]|WHERE_LTE|reassignmen<br>t_countWHE<br>RE_LTE2|Extract<br>records<br>where the<br>value in the<br>**Reassignme**<br>**nt count** field<br>is one of the<br>following:<br>**•** a number<br>less than 2<br>**•** 2|
|Where not<br>equal|[Impact]<br>[WHERE_NEQ<br>][1 - High]|WHERE_NEQ|impactWHER<br>E_NEQ1|Extract<br>records<br>where the<br>value in the<br>**Impact** field<br>is anything<br>but**1 - High**.|


|Operator label|Example condition|Equivalent query operator|Example query|Example output|
|---|---|---|---|---|
|Where not<br>empty|[Impact]<br>[WHERE_NOT<br>EMPTY]|WHERE_NOT<br>EMPTY|impactWHER<br>E_NOTEMPTY|Extract<br>records<br>where the<br>**Impact** field<br>has any<br>value.|
|Where not<br>one of|[Impact]<br>[WHERE_NOT<br>ONEOF][1 -<br>High, 2 -<br>Medium]|WHERE_NOT<br>ONEOF|impactWHER<br>E_NOTONEO<br>F1,2|Extract<br>records<br>where the<br>**Impact** field<br>is populated<br>by anything<br>except the<br>following<br>values:<br>**• 1 - High**<br>**• 2 -**<br>**Medium**|
|Where one<br>of|[Impact]<br>[WHERE_ONE<br>OF][1 - High,<br>2 - Medium]|WHERE_ONE<br>OF|impactWHER<br>E_ONEOF1,2|Extract<br>records<br>where the<br>**Impact** field<br>is populated<br>by one of<br>the following<br>values:<br>**• 1 - High**<br>**• 2 -**<br>**Medium**|


## **Add repeaters to components**


In UI Builder, use repeaters to repeat one or more components with results
from a data resource.


**Before you begin**


Role required: ui_builder_admin


**About this task**


The repeater component acts as a basic loop that repeats the data
you provide in multiple components within UI Builder. Repeaters use
an array or an array of objects. For example, the array `[{"task":`
`"A"},{"task": "B"}]` repeats the content inside it two times.
Repeaters enable you to bind values to a data array property.
`@item.value.{property_name}` binds the values to the component
inside the repeaters. If you want to bind a task, you can bind it as
`@item.value.task`, and the repeater displays the correct value.


Components inside a repeater repeat the number of items in the data
source, regardless of whether the component output is made dynamic
or not. For example, say that you place a Header component inside a
repeater with three data elements but don't change the Label field. Then
you see three instances of the Header with the same output Label.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open the editor for the page where you want to add the repeater.
If you haven't created a page for your experience, see Create a
page in UI Builder for more information on how to create a page.


4. Connect a data resource to your page.


For example, add the **Look up multiple records** data resource to your
page. See Add and configure data resources to a page for more
information on connecting a data resource.


a. In the data resource drawer, select **+ Add data resource** .


b. In the modal, search for the **Look up multiple records** data
resource and select **Add** .


c. In the **Table** field, enter `Incident` .


d. In the **Max results** field, enter `5` .


The **Look up multiple records** data resource is configured.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-622-1.png)


e. Close the modal.


5. Select an existing container or create a column layout.
See Organize components in UI Builder pages for more information.


6. Add the repeater component to your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-623-1.png)


For information about adding components, see Add and configure
components.


7. In the **Configure** tab, select **None - Configure the component**
**manually** .


8. In the **Configure** tab, add an array that defines the data for
repeated components.


a. Point to **Data array** and select the Bind data icon ( ).


b. Under **Data types**, select **Data resource** .


c. In the next column, select the **Look up multiple records 1** pill.


d. Under **Pill view**, double-click or drag **results** to add the
**@data.look_up_multiple_records_1.results** output.


e. Select **Apply** .


The results from the data resource are bound to the repeater
component. Within the repeater, one component represents
each result.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-624-1.png)


9. Under the repeater that you added in the previous step, select **+ Add**
**content** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-625-1.png)


10. Add a **Heading** component.


11. In the **Configure** tab, select **None - Configure the component**
**manually** .


12. Configure the component you nested in the repeater.


For example, bind the **displayValue** to the component. See Connect
data to your components for more information.


a. Move your cursor to the **Label** field and select the Bind data icon


( ).


b. Under **Data types**, select **Repeater** .


c. Under **Pill view**, select the **value** pill.


d. In the next column, select the **number** pill.


e. In the next column, double-click or drag **displayValue** to add the
**@item.value.number.displayValue** output.


f. Select **Apply** .


The **displayValue** is bound to the Heading component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-626-1.png)


13. Select **Save** .


The component you bound to the data resource appears on the
stage and is repeated five times, once for each result returned from
the Incident table.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-627-1.png)


14. View and test your page by selecting the **Preview** button.
A tab opens to display the page preview with repeated data.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-628-1.png)

## **Optimize page loading performance (Advanced** **Feature)**


Performance settings enhances leading speeds and user engagement
by displaying high-priority content first, making key components
interactive sooner for a faster perceived performance.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. Add a component to your page.
You need a component on your page before you can adjust
performance settings.


5. Select the menu icon.


6. Select **Manage performance settings** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-629-1.png)


The **Advanced performance settings** modal opens.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-630-1.png)


7. Select how components load onto a page.

|Choice|Description|
|---|---|
|Progressive loading|Enable quicker page access<br>while components continue to<br>load.|
|Full page loading|Ensure a seamless experience<br>by loading all content before<br>you access the page. Enter the<br>maximum time you want to wait<br>before displaying content in the<br>**Page loader threshold duration**<br>field.|


8. Select the priority in which components load on a page.


a. Select the **Priority** tab.


b. Select the component you want to give priorty to.


c. Check **Make high priority** .


9. Select which data to cache when a page loads.


a. Select the **Cache and headers** tab.


b. Select a data resource from the list.


c. Check **Activate data policy** .


10. Select **Apply** .

## Dynamically expose data in UI Builder pages (advanced feature)


Sync data between ServiceNow tables and data with the pages you
build with UI Builder. Pages display synced data in real time and update
data/tables when a user inputs information.


**Learning about data resources in UI Builder**


UI Builder syncs ServiceNow tables/data using data resources. A data
resource fetches the data that UI Builder uses to display information
in a component. UI Builder components use data resources to sync
data across different experiences. Data resources make the data in
components dynamic, which means that you don't have to recreate
data for every page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-632-1.png)


Data resources are found in the data resource drawer. The data resource
drawer is where you can add and configure a data resource for your
page. After you configure the data resource, you can sync the data
between components on your page and ServiceNow tables/data.


Data Resource Drawer

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-633-1.png)


The data resource drawer contains three sections:


**•** Data resources: The data resources that are part of the experience


**•** Configuration/Events: Configured data resources and events for the
experience


**•** Preview: JSON for the information returned by the data resource


You can bind the configuration properties for components, other data
resources, client scripts, client state, and events to these data resources.


Set conditions for a filter in your data resource. For more information, see
Connect data to your components.


**How data resources work in UI Builder**


Data resources fetch data from Glide, GraphQL, and REST APIs, then
transform it for use in a component on a UI Builder page.


Components use both inherited and local data resource instances.
Inherited data resources are automatically loaded into a UI Builder page,
and local data resource instances can be added and configured. Data
resources are evaluated based on specified input values to make sure
the right data is retrieved. For more information about inherited and local
data resources, see Inherited versus local data resources in UI Builder.


**Local data resources in UI Builder**


You can select local data resources, such as server data, operations,
transforms, or client data, like the gForm API, to bring data to the UI
Builder page.


**Note:** Only one GlideForm is supported per page in UI Builder. For
[more information about GlideForm, see the ServiceNow Developer](https://developer.servicenow.com/dev.do#!/reference/api/vancouver/client/c_GlideFormAPI)
[site.](https://developer.servicenow.com/dev.do#!/reference/api/vancouver/client/c_GlideFormAPI)


Data resources are organized by application in the data resource
drawer. They are then further categorized by the data resource type
like Server data or Transform. For example, the Global application has
several data resources, but the Customer Service Management (CSM)
Workspace application has only a few data resources.


Data resources

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-635-1.png)


You see different data resources depending on the application that you
are in. If you select the Global application, you will see different data
resources under Server data than if you select the CSM Configurable
Workspace application.


**Using data binding in UI Builder**


Data binding enables you to create dynamic pages by syncing pages
and components to data resources. You can bind data to a component
to retrieve data from the back end, and use field parameters to get
properties from the URL. Changing the URL parameters enables you


to create dynamic pages that show different data depending on the
parameters.


You can bind data to a component in the following ways:


**Context binding**


Use URL parameters to connect parts of the URL with your page's
properties. For example, you can link the table name from the
URL to your component by using the @context syntax, like this:
`@context.props.table` .


Imagine you have a UI Builder page with a required field named `table` .
The URL for your page might look like /demo/page/<table-name>. The
<table-name> could be something like `incident` . The data can also
come from parent data resources or be local properties specific to the

page.


To link your component properties, other data resource properties, or
event details to the page property, you use a `@context.props.table`
binding. Be sure to either provide a test value in the URL or set a fixed
value for that property in your page's configuration if you are using
context binding.


**Data resource binding**


Use data resources to fetch data from the back end of your instance,
such as Client state, GraphQL, or a REST API. These data sources have
properties that can be linked to elements on a UI Builder page.


For instance, if you are using the Lookup Record data
resource, you can utilize it in a button component. You
might use a data expression in the "label" property like this:
`@data.lookup_record_1.result.number.displayValue` .


**Component binding**


Use component binding to connect one component to another. Let's say
that you have a List Menu component on the UI Builder page. The List
Menu reveals the currently chosen list to other components on the same
page. These other components can access the data by linking to it using
an expression such as `@elements.list_menu_1.selectedListId` .


**Client state parameter binding**


Use client state parameter binding to connect and synchronize data
between a client-side application and UI Builder components. Parameter
binding allows the client state to automatically update data in
components, and vice versa. Use `@state` syntax to bind a state property
to a client state parameter.


**Types of data sources available in UI Builder**


You can use the following data resource types that are shown in the
table.


**Data resource types**


|Data resource type|Description|
|---|---|
|Controller|Encapsulates data and event<br>logic and enables presets for<br>components.|
|GraphQL|GraphQL queries and mutations<br>that are executed.|
|Transform|Script that transforms the input<br>data into another format.|
|Client state|Client-side data resources that<br>include the client information,<br>domain-specific states or logic,<br>user preferences, and so on.|
|Composite|Single reusable data resource that<br>contains multiple data resources.|
|REST|Data resources that are made<br>through REST API requests.|


**Inherited versus local data resources in UI Builder**


Inherited data resources share information from the surrounding parts of
a UI Builder page such as an application. Imagine your page is in a large
frame, and it gets some information from the frame or other parts around


it. You can use this info by connecting it to your page's properties, kind
of like linking puzzle pieces together. If you get this information from the
frame, you don't have to get it again yourself.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-638-1.png)


Local data resources are items you add to a UI Builder page yourself.
Imagine you're making a page for travel requests. You can sync
employee data to a list component so employees can request trips
linked to their own info.


To use these data resources, either bring them in from an app or
create them in the ServiceNow platform. Then, in UI Builder, make these
resources available for your components. Next, tie the data to your
component, so it can work with it. For instance, you could have a set
of records, expose it in UI Builder, and link it to a component. From there,
configure the component to do things with the data, like saving new
records.


Once your page is syncing data, you connect it to the part of the page
that needs it such as a component. It's like making sure the right puzzle
piece fits in the right spot. Then you can tell that part of the page what to
do with the data. For example, you might use it to add new travel plans
for employees.


**UI Builder Data resource properties**


When you add a data resource in UI Builder, it's like adding a tool that
knows where to get information from. Data resource properties are the
instructions that tell a data resource how to bring data into UI Builder
pages. These properties tell a data resource which data to get, how
to organize it, and what conditions to follow. For instance, you can
use these properties to specify which tables to look in, how to sort the
data, and more. These properties are what make the data resource work
correctly and give you the data you need.


After adding a data resource, you can choose to load it either eagerly or
explicitly. Use the descriptions below to determine which approach best
fits your page. This decision can impact performance, user experience,
and resource efficiency, so it's important to understand the differences.


**Immediately (eager evaluation)**


Data loads automatically when the page or component loads.


Useful for core content the user expects to see right away.


May slow down loading of pages and components by fetching unused
data.


**Only when invoked (explicit evaluation)**


Defers data loading until a user takes a specific action. For example,
clicking a button or entering data in a field.


Saves resources by only fetching data when needed.


Speeds up initial page loading.


Data resource evaluation options

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-640-1.png)


**UI Builder Data resource scripts**


Data resource scripts are special instructions you give UI Builder to return
specific pieces of data. For example, if you're dealing with a list of
products, a script could tell a data resource to show only products
that are available in stock or to arrange them in a particular order.
Data resource scripts enable you to customize how UI Builder treats the
information, such as adding extra rules or actions.


**•** Add and configure data resources to a page


Add data resources to dynamically expose data from tables, records,
or other elements on your page in UI Builder.


**•** Add Now Assist skills to your page


Add skills to enhance your UI Builder page with Now Assist's generative
AI capabilities.


**•** Bind data to UI Builder pages using controllers (advanced feature)


Controllers simplify the linking of data and event logic to enable
component presets in UI Builder.


**•** Create custom controllers (Advanced feature)


Build custom controllers to use across experiences. Easily connect
reusable data, scripts, and events to your page and set up inputs,
outputs, and events.


**•** Connect data components


Use the data binding modal to associate data exposed by local data
resources to components on your UI Builder page.


**•** Client state parameters


Use client state parameters to bind values to component
configurations. When the client state parameter's value changes, the
component updates to use the new value.


**•** Define and bind client scripts to components


Add and edit client scripts in UI Builder so that you can update
the client state through events. You can bind these scripts to any
component by using an event handler.


**•** Multi-table data configuration


Present data from multiple tables using components and control the
layout and styling.


**•** Work with the Entity View Action Mapper for UI Builder


With UI Builder, you can use the Entity View Action Mapper (EVAM)
application to standardize how the data sources in your components
are displayed in your cards and lists.

## **Add and configure data resources to a page**


Add data resources to dynamically expose data from tables, records, or
other elements on your page in UI Builder.


**Before you begin**


Role required: ui_builder_admin


Choose the application containing your data resource. The Global
application contains the most common data resources. The data
resources relate to Server data, Operations, and Transform. You can add
a data resource such as Look Up Records, Table route map, GlideRecord
Query, and so on.


**About this task**


In the data resource section of UI Builder, you can add and configure
local data resource instances for your page. Local data resource
instances dynamically expose data to components. If you have any
inherited data resources, they are listed in the inherited data resource
pane and are read-only. You don’t configure inherited data in UI Builder.
Data resources from any application can be added to any page unless
restricted by security permissions. You can add multiple local instances of
the same data resource, if you need different configurations of the same
data resource on your page.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. Add a component to your page.
You need a component on your page before you can bind a data
resource to it.


5. Select the **+** icon in the data resource drawer.


6. Select **Data resource** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-643-1.png)


7. Select a data resource to add to your page.
For example, you could select **Look up a single record** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-644-1.png)


8. Select **Add** to add the data resource to your page.
The Data Resource configuration modal appears.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-645-1.png)


9. Fill in the required information for the data resource in the **Configure**
tab to expose the data you want.
The configuration fields vary depending on which Data Resource
instance is selected. The **Configure** panel and preview window may
display errors when a Data Resource is added to a page. UI Builder
attempts to evaluate Data Resources when they’re added to a
page. The errors remain until the required Data Resource fields have


been filled.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-646-1.png)


10. Select the default label to provide a custom label and ID value.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-647-1.png)


The data resource appears in the data and scripts drawer.


11. Select **Save** in the UI Builder header.


**What to do next**


Now that you have a data resource connected to your page, you can
bind the data to a component or bind an event to the data resource. For
more information, see Connect data to your components and Bind an
event to a data resource.

## **Add Now Assist skills to your page**


Add skills to enhance your UI Builder page with Now Assist's generative AI
capabilities.


**Before you begin**


Role required: ui_builder_admin


**Note:** Skills must be enabled and activated before they can be
added to a page. For more information, see:


**•** [Configure skill deployment settings: Enable the skill to make it](https://www.servicenow.com/docs/csh?topicname=configure-skill-settings&version=zurich&pubname=zurich-intelligent-experiences)
available for selection


**•** [Activate a skill: Activate the skill so it can be selected](https://www.servicenow.com/docs/csh?topicname=activate-skill&version=zurich&pubname=zurich-intelligent-experiences)


**About this task**


You can add Now Assist skills to your page, component, or controller. To
trigger a skill, you must create an event to execute the skill while passing
the appropriate payload. After configuring the required inputs, the skill is
ready to use.


In this example, you will:


1. Add a skill to the page


2. Add an input component to capture user text


3. Configure an event for the input component to pass the entered text
to the skill and execute it


4. Add a text component to show the skill's output


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. Hover over **Now Assist skills** in the **Data and scripts** section and select
the **+** to the right.


5. Select a skill and select **Add** .
The following skills are available by default:


**• Generate Content**


**• Sentiment Analysis**


**• Summarize**
For this example, select **Generate Content** .


**Tip:** Select **Hide inactive** to remove inactive skills from view.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-649-1.png)


**Note:** Skills that are enabled in Now Assist Skill Kit but not
activated in Now Assist Admin appear in the list, but aren't
[selectable. For more information, see Now Assist Skill Kit and Now](https://www.servicenow.com/docs/csh?topicname=now-assist-skill-kit-landing&version=zurich&pubname=zurich-intelligent-experiences)
[Assist Admin console.](https://www.servicenow.com/docs/csh?topicname=configuring-now-assist&version=zurich&pubname=zurich-intelligent-experiences)


6. Select the **X** in the upper right to close the **Edit Generate Content**
dialog.


7. Select **+ Add content** in the content tree and add a component from
the toolbox.
In this example, add an **Input** component.


8. Add the **Execute** event handler to the component that you added in
the previous step.


a. Select the **Events** tab in the configuration panel.


b. Select **Add handler** under **Text entered** .


c. Select **Execute** under **Generate Content (1)** and select **Continue** .


d. Hover over **topic** and select the bind data icon to configure
the input for the skill.


e. Double-click the **fieldValue** pill to select it as the input source and
select **Apply** .


The **fieldValue** property captures what the user types in the input
field. By using this property as the input to the skill, you set the skill
to trigger whenever the user enters text.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-651-1.png)


f. Select **Add** .


9. Add and configure a second component to display the output for
the skill.


a. In the content tree, hover over **Input 1**, select the **Configure**
(three vertical dots) icon, then select **Add after** .


b. Add a **Stylized text** component.


c. Select **Cancel** to close the preset window.


d. (Optional) Change the **HTML tag** property to **Paragraph** (for
better readability in this example).


e. Hover over the **Text** field in the configuration panel and select


the bind data icon .


f. Select **Data resource** on the left.


g. Navigate through the pills by selecting **Generate Content**, then
**result**, then double-clicking **response** to complete the selection.


h. Select **Apply** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-653-1.png)

10. Select **Save** .


11. Select **Preview** to test the skill.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-654-1.png)


**Result**


When you view the page and type in the input field, your text input
triggers the **Generate Content** skill to execute and return content on the
topic in the input field.


## **Bind data to UI Builder pages using controllers** **(advanced feature)**


Controllers simplify the linking of data and event logic to enable
component presets in UI Builder.


Controllers enable page builders to easily connect data and scripts
to their pages in UI Builder. A controller is a type of data resource
that component presets use to bind data to components. Controllers
differ from other data resources in that they contain data and event
logic that enables presets for components. A controller brings data from
the server to a component, and it brings updated data back to the
server based on interactions with the component. For more information
about component presets, see Automatically configure components
using presets.


Controllers are added by default when you use a UI Builder page
template. You can add controllers to UI Builder pages without a controller
within the data resources drawer or by selecting a component preset
after adding a component to a page. You can view which controllers
are configured on your page by opening the data resources drawer.


Controller in the Data resource drawer

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-656-1.png)


**Types of data controllers in UI Builder**


**Data controllers**


Data controllers decide what information should be displayed on UI
Builder pages. Data controllers use data resources to sync information
in real time and update data/tables when a user inputs information. You
can manually add data controllers to a page.


**UI controllers**


UI controllers are added to pages when using UI Builder page templates
and cannot be added manually.


**Using controllers with presets in UI Builder**


You can add multiple controllers to a UI Builder page, but you can't use
the same one twice. If you try to use a component preset that needs a
controller, UI Builder prompts you to add it.


Not all components work with controllers, but you can easily see which
ones do in the component library. If you have a controller configured
on your UI Builder page, you can open the component library to view
which components have presets. Components with presets available are
highlighted in the component library.


Components with presets

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-658-1.png)


**Add a controller**


Add a data controller to your page to use component presets.


**Before you begin**


Role required: admin


**About this task**


The record controller is the only controller that you can add to a page in
Zurich.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Create or open a page or page variant.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select the **+** icon in the data resource drawer.


5. Select **Data resource** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-660-1.png)


6. Enter `form` in the search field.


7. Select the controller you would like to add to your page.


8. Select **Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-661-1.png)

9. Fill in the fields to configure the controller.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-662-1.png)


**Result**


The form controller displays in the **Data resources** section.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-663-1.png)


**Edit a controller**


Configure a controller to pull data from a table.


**Before you begin**


Role required: admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Create or open a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. Select the controller that you want to edit in the **Data and scripts**
drawer.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-664-1.png)


5. On the form, fill in the fields.


**Form controller form**


**Field** **Description**


|Type|Controller is predefined as the<br>type for all controllers.|
|---|---|
|Table|Add a table that you want the<br>controller to pull data from.|
|Sys ID|Enter the unique identifier for a<br>record, provide a value, or use -1<br>to generate a new value.|


6. Close the edit controller modal.


7. Select **Save** .


**Delete a controller**


Delete a controller that you no longer need in UI Builder.


**Before you begin**


Role required: admin


**About this task**


Controllers cannot be deleted from pages created with a page
template.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open the page with the controller you want to delete.


4. Select the **Menu** icon ( ) next to the controller you want to delete.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-666-1.png)

5. Select **Delete** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-667-1.png)


The controller is removed from the local data resource instances.


**View properties and events in the Controller API**


The controller public API defines the output data that a controller
provides to a preset. This includes the property values and handled
events used by a component when a preset is selected. Property and
event information is available to view in UI Builder.


The component property values in a preset can be static values or paths
to controller output data. You can use the data resource inspector in UI
Builder to display the values from the controller data structure used by a


preset. To view the payload carried by an event in the preset, you can
look in the event handler picker for that event.


**Viewing properties in the Controller API**


You can view preset properties in the UIB data inspector. Knowing the
available values helps you understand how a component will behave in
your design and helps you identify any properties in the preset you might
want to override.


This procedure assumes that you have placed a component with a
preset on the page and have configured a controller. For instructions,
see Add a controller.


The configuration tab displays preset property values as a path
to the controller output. The base data path is expressed as
`@data.<controller_name>` . The remainder of the path is built using the
contents of the categories within the controller data hierarchy. You can
use this path to view the current values for the record for which the
controller has been configured.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-669-1.png)


1. To view the data resources for a component, select the data icon in
the lower left sidebar.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-670-1.png)


The three column UIB data inspector appears.


2. In the first column where the data resources are listed, select the
controller whose output you want to view.
The configuration data for the selected controller appears in the
Config tab of the second column. These are the input properties you
entered when you configured the controller for the first component
with a preset you placed on the page. You can edit these
connection values here if you want.


**Note:** Configuring **-1** for the value in the **Sys ID** field configures
the controller for a new record. The controller then generates
a full GUID that you can use to store data against the record
before it's saved. This allows you to perform actions in a newly
created record such as saving attachments.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-671-1.png)


3. Select **top level outputs** in the third column.


This is the parent level of the controller data hierarchy, indicated
with the prefix `@data.`, followed by the controller ID. This combination
forms the root path to the data. The data contained in the top level
outputs are displayed in the adjacent code field and are available
for presets and scripts to use. Other properties at that level are some
common properties that apply to all records.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-672-1.png)


When the preset maps a component property to controller output,
the path to the output is shown instead of the value. Paths are
denoted as **@data.<controller id>.<path from top level to output**
**property>** and can be used as the values or as part of formula
expressions.


In this example, the mapping in the preset results in a path to
`@data.gform.table` .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-673-1.png)


4. To view data below the top level, select the child category indicated
by the path in the preset property value.


The name of the child category appears in the path as
`@data.<controller ID>.<category>` . The data from that
category is then appended to that path. The root path above the
code field indicates the child category being used. In this example,
the path to the **View** property in the `form` category is expressed
as `@data.gform.form.view` . That preset value displays forms in the
**workspace** view.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-674-1.png)


In this example, multiple controller output properties are used in a
formula expression to build an object.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-675-1.png)


5. To view a scripted property value, select the lock icon next to the
property.


This puts the property into edit mode and opens a modal for editing
the script.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-676-1.png)


**Viewing events in the Controller API**


You can view handled events mapped to a component by a preset and
their payloads in the Events tab in the UI Builder configuration panel. If
the data mapping for an event isn't appropriate for your use case, you
can add additional data handlers.


**Note:** Data handler mappings provided with the preset are not
editable.


1. Select the Events tab in UI Builder.


2. To view the mapping for a preset event, select the event tile.


A modal appears showing the payload properties for the preset
event. You can **Disable** the event in this modal.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-677-1.png)


3. To add an event handler to the event, select **+ Add event handler**
under the event tile.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-678-1.png)


A modal appears, showing a list of available, handled events. You
can select any action from the list, including an event handler from
one of the controllers listed.


4. Select an event handler from the list and select **Add** .


The new handler is listed under the event tile.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-679-1.png)

## **Create custom controllers (Advanced feature)**


Build custom controllers to use across experiences. Easily connect
reusable data, scripts, and events to your page and set up inputs,
outputs, and events.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Select **Create** .


3. Select **Controller** .


4. On the form, fill in the fields.


**Create a page collection form**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-679-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-680-1.png)


5. Select **Create** .
The controller building window opens.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-680-2.png)


6. Add data resources.


a. Select **+ Add data resource** .


b. Select a data resource from the list.


c. Select **Add** .


d. Configure the data resource.


e. Select **Save** .


7. (Optional) Add an external controller dependencies.


a. Select **+ Add external controller dependency** .


b. On the form, fill in the fields.


**Edit external controller dependency**


**Field** **Description**


|Name|Name to identify your external<br>controller dependency.|
|---|---|
|Label|Label to help find your external<br>controller dependency.|
|Controller|Select a controller for<br>your external controller<br>dependency.|


c. Select **Save** .


8. (Optional) Add client state parameters.


a. Select **Client sate parameters** .


b. Select **+ Add** .


c. Enter a unique name for the client state parameter.


d. Select the type from the dropdown.


e. Enter an initial value in the field.


f. Select **Save** .
For more information about client state parameters, see Client state
parameters.


9. (Optional) Add client scripts.


a. Select the **+** icon next to **Client scripts** .


b. Write your script to perform an action.


c. (Optional) Add a **Script include** or **Associated components**,
which shows up in the `imports` parameter of your client script
function.


d. Select **Apply** .


e. Select **Save** .


**What to do next**


Use the custom controller you just created by adding the controller to a

page.

## **Connect data components**


Use the data binding modal to associate data exposed by local data
resources to components on your UI Builder page.


**Data binding modal**

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-682-1.png)


**Data binding modal options**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-683-1.png)


|Undo|Undo the previous change.|
|---|---|
|Redo|Redo a change that has been<br>undone.|
|Bind data using drag and drop|Show Pill view.|
|Use script|Show JSON view.|
|Toggle full screen|Expand the data binding modal<br>to full screen size. Select again to<br>reduce the data binding modal to<br>smaller size.|
|Close|Close the data binding modal. If<br>you have unsaved changes, you<br>are given the option to save.|
|Data types|Lists page properties, data<br>resources, and client states.|
|Formulas|Lists formulas that can be used. A<br>search field is available.|
|Pill view|When**Data types** is selected, pill<br>view enables you to specify a<br>property value or display value.<br>You may have to select several<br>pills to get to a specific value.|
|JSON|When**Data types** is selected, the<br>JSON option enables you to edit<br>the raw JSON code.|


There are two methods you can use for binding data: drag and drop,
and editing JSON.


**Binding data with drag and drop**


Use this method if you want to use a visual process.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-684-1.png)


Use the search bar to find the data you would like to bind to your
component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-685-1.png)


**Binding data by editing JSON**


Use this method if you are comfortable working in and editing JSON
code.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-686-1.png)


**•** Connect data to your components


Bind data exposed by local data resources to components on your UI
Builder page.


**•** Connect data to your components with formulas


Bind data exposed by local data resources to components with
formulas on your UI Builder page.


Bind data exposed by local data resources to components on your UI
Builder page.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Data binding is the process of associating data with a UI element that
displays the information. Before binding data to components you must
add a data resource to your UI Builder page, see Add and configure
data resources to a page for more information.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. Add a data resource to your page.
For more information, see Add and configure data resources to a

page.


5. Add a component to your page.
You need a component on your page before you can bind a data
resource to it. For more information, see Customize UI Builder pages
using components.


6. Select the **Configure** tab from the configuration panel in UI Builder.


7. Point to a field that you want to bind data to and select the dynamic


data binding icon ( ).

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-687-1.png)


The data binding modal appears.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-688-1.png)


8. Select **Data resource** in the **Data types** tab.


9. Select the data resource that you want to bind to the component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-689-1.png)


10. Select and drag the data you want to bind to the component into
the field above.


You may have to select several pills to get to a specific property
value or display value.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-690-1.png)


11. Select **Apply** .


The component displays the property value or display value that
you've selected.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-691-1.png)


12. Select **Save** in the UI Builder header.


Bind data exposed by local data resources to components with formulas
on your UI Builder page.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Data binding is the process of associating data with a UI element that
displays the information. Before binding data to components you must
add a data resource to your UI Builder page, see Add and configure
data resources to a page for more information.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.


4. Add a data resource to your page.
For more information, see Add and configure data resources to a

page.


5. Add a component to your page.
You need a component on your page before you can bind a data
resource to it. For more information, see Customize UI Builder pages
using components.


6. Select the **Configure** tab from the configuration panel in UI Builder.


7. Point to a field that you want to bind data to and select the dynamic


data binding icon ( ).

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-692-1.png)


The data binding modal appears.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-693-1.png)


8. Select the **Formulas** tab.


9. Select and drag the formula you want to bind to the component into
the field above.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-694-1.png)


For more information about formulas, see Supported functions in the
UI Builder component formula editor.


10. Fill in the fields of the formula.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-695-1.png)


11. Select **Apply** .


The component displays the property value or display value that
you've selected.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-695-2.png)


12. Select **Save** in the UI Builder header.


## **Client state parameters**


Use client state parameters to bind values to component configurations.
When the client state parameter's value changes, the component
updates to use the new value.


**What is a client-side interaction**


In web-based applications, anything that happens in the browser
is client-side. Client-side interactions occur when users interact with
experience components by clicking. Examples of client-side interactions
include:


**•** Clicking a button


**•** Applying a filter


**•** Sorting a list


**•** Refreshing a list


**•** Providing inline search results


**•** Alerting a user to incomplete or incorrect data

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-696-1.png)


Users sometimes interact with pages in order to navigate to other pages.
In other cases, users want to make updates to a page's content,
appearance, or data. Rather than refreshing the entire page, client-side
interactions update only the affected parts of a page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-697-1.png)


For example, a user can sort a list by clicking a column header. Sorting
redraws only the list and not the entire page.


Creating client-side interactions in UI Builder involves:


**•** Client state parameters


**•** Events


**•** Client scripts


**What are client state parameters**


Client state parameters are page variables. Define and configure a
client state parameter and use the value to configure components.
Client state parameters centralize management of configuration values
for page components. UI Builder uses client state parameters to enhance
user experience and provide personalized content and services.


**Example of client state parameters**


In the example, a page has a client state parameter called color.
Two of the three components are configured to use the color client
state parameter. If color is set to orange, the components are orange.
If color is set to purple, the components are purple. If color is set to
green, the components are green. The client state parameter is a single
place to manage a common value for the page. Without the client
state parameter, each component that uses a value would need to be
updated individually if that value changed.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-698-1.png)


For example, a web experience stores the primary color used by
components in the color client state parameter. When the components
are configured to use the client state parameter, changing the value of
the client state parameter updates the components to the new value.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-699-1.png)


Buttons can be added to the experience to allow users to select a color
for the page components. With a single click, a user can simultaneously
change the color of all components on a page. Store the user’s color
choice in a client state parameter, then use the client state parameter
to configure the page’s components. When a user interaction causes
the client state parameter value to change, the page’s components are
updated in real time.


**The client state panel**


The client state panel is collapsed by default. Click the client state icon in
the left navigation bar to open the client state panel.


The client state panel contains two sections:


**•** Client state parameters: The client state parameters for the page


**•** Client state preview: The JSON for the page's client state parameters


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-700-1.png)


**Creating client state parameters**


To add a client state parameter to a page, click the **+ Add** button in the
client state parameters section.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-701-1.png)


Client state parameters have three configuration fields.


**•** Name: The name of the parameter. Names should not include spaces


**•** Type: The parameter's type


**•** String


**•** Number


**•** Boolean


**•** JSON


**•** Initial value: The default value for the parameter


In the example, the client state panel has two client state parameters.


**•** `occasionTypeQuery` is a string with no default value


**•** `occasionListTitle` is a string with a default value of `All Special`
```
 Occasions

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-702-1.png)

```

**Working with client state parameters**


Once you have a client state parameter, what can you do with it?
To work with client state parameters, first bind the value of the client
state parameter to component configurations. When the client state
parameter's value changes, the component updates to use the new
value. One way to change a client state parameter's value is with event
handlers.


In the creating client state parameters page example, two
client state parameters were added to the special occasions
application: `occasionTypeQuery` and `occasionListTitle` . The
`occasionTypeQuery` parameter has no value by default and
`occasionListTitle` has the default value `All Special Occasions` .
These client state parameters will be applied to the Occasion List
component to set the list's title and filter. A button will be used to update
the values of these client state parameters to dynamically update the list.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-703-1.png)


**Binding client state parameters**


Client state parameter values can be bound to component
configuration fields the same way page context, payload, and data
resources are. When configuring components, hover over a field, then


select the **Dynamic data binding** button ( ) to bind a client state
parameter to the field value. In the example, the **Dynamic data binding**
button is highlighted for the Occasion List component's filter field.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-704-1.png)


The character @ indicates data binding and the state object contains
the client state parameters. Select a client state parameter from the
choice list. The example shows selecting the `occasionTypeQuery` client
state parameter. The default value for the `occasionTypeQuery` client
state parameter is empty, so no filter will be applied by default.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-705-1.png)


The Title for the component is set in a similar manner: select the
**Dynamic data binding** button for the Title field or type @, then select
the **state.occasionListTitle** client state parameter from the choice list.
The default value for the `occasionListTitle` client state parameter
is `All Special Occansions` . The example shows both Title and Filter
configured to use client state parameters.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-706-1.png)


With both client state parameters applied, no filter is applied to the list
and the title is `All Special Occasions` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-706-2.png)


The `occasionTypeQuery` and `occasionListTitle` client state
parameter values remain unchanged until a user interacts with a
component that changes the value of the client state parameter.


**Change client state parameter values**


User the **Update client state parameter** event handler to change the
value of a client state parameter in runtime. The **Update client state**
**parameter** event handler has two properties: client state parameter to
update and the new value to use for the client state parameter.


As an example, a `Birthdays` button is added above the `Occasion`
`List` component in the `Special Occasions` application. The objective
of this button is to change the `Title` of the list to `All Birthdays`
and to adjust the filter of the list to only show birthdays. To achieve
this objective, two event handlers are mapped to the **Button clicked**
event for the button, one to change the `occasionTypeQuery` client
state parameter and another to change the `occasionListTitle` client
state parameter. The image shows the **Update client state parameter**
event handler configured to set the `occasionTypeQuery` client state
parameter to `special_occasion=birthday`, which will filter the list to
only show birthdays.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-708-1.png)


When the **Button clicked** event is mapped to event handlers to update
both the `occasionTypeQuery` and `occasionListTitle` client state
parameters, clicking the button updates the client state parameters,
which automatically updates the `Occasion List` component with the
new values.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-709-1.png)


**•** Using client state parameters in UI Builder


Create a simple counter by adding the stylized text component and
two buttons to an experience page. Use a client state parameter to
implement the functionality so that when the buttons are selected the
count increases or decreases.


**•** Update a component’s state using client state parameters


Create and bind a client state parameter value to a component
in UI Builder. By adding custom values to your components, these
components can then be automatically updated through a script.


Create a simple counter by adding the stylized text component and
two buttons to an experience page. Use a client state parameter to
implement the functionality so that when the buttons are selected the
count increases or decreases.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page in UI Builder or open a page.


4. Add a column layout by selecting **+ Add content** in the content tree
under **Body** .


5. On the **Layouts** tab, select **Two columns** .


6. Add the first component by selecting **+ Add content** in the content
tree under **Column 1** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-711-1.png)

a. In **Search**, type `sty` .


b. Select the **Stylized text** component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-712-1.png)


c. In the configuration panel, select **None - Configure the**
**component manually** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-712-2.png)


7. Add the second component by selecting **+ Add content** in the
content tree under **Column 2** .


a. In **Search**, type `button` .


b. Select **Button Iconic** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-713-1.png)


c. In the configuration panel, select **None - Configure the**
**component manually** .


d. In **Icon**, select **Square Arrow Up Fill** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-713-2.png)


8. Add the third component by pointing to **Button iconic 1** in the
content tree, selecting the **Menu** icon, and selecting **Add after** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-714-1.png)


a. In **Search**, type `button` as you did in the previous step.


b. Select **Button Iconic** as you did in the previous step.


c. In the configuration panel, select **None - Configure the**
**component manually** as you did in the previous step.


d. In **Icon**, select a different icon this time, the one named **Square**
**Arrow Down Fill** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-715-1.png)


9. Select **Save** .
The stylized text component and the two button iconic components
are saved and appear on the stage.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-715-2.png)


10. Add a client state parameter by going to **Data and scripts**, pointing
to **Client state parameters**, and selecting the **Add new (plus)** icon.


a. Change the **Name** by entering `count` .


b. Change the **Type** to **Number** .


c. Set the **Initial value** by entering the number `0` .


d. Select the **X** to close the window.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-716-1.png)


11. Bind the stylized text component to the client state parameter.


a. Select the stylized text component on the stage.


b. In the configuration panel, point to the **Text** field and select the
**Bind data or use scripts** icon.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-716-2.png)


c. On the **Data types** tab, select **Client states** .


d. Double-click on the **count** pill.


e. Select **Apply** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-717-1.png)


The **Text** field changes to **count** .


12. Now configure the buttons to increase or decrease the number.


a. Select the top button on the stage.


b. In the configuration panel, select the **Events** tab.


c. Select **+ Add event handler** .


d. Under **Page-level event handlers**, select **Update client state**
**parameter** .


e. In **Client State Parameter Name**, select **count** .


f. Point to the **New Value** field and select the **Bind data or use**
**scripts** icon.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-717-2.png)


g. On the **Data types** tab, select **Client states** .


h. Double-click on the **count** pill.


i. Select the **Formulas** tab.


j. In the list, select **Math** .


k. Double-click on the **ADD** pill.


l. In the **right** pill at the top, remove the text and enter `1` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-718-1.png)


m. Select **Apply** .


n. Select **Add** .


13. Now configure the second button by following the same process that
you used for the first button, but select the SUB pill instead of the ADD
pill.


a. Select the bottom button on the stage.


b. In the configuration panel, select the **Events** tab.


c. Select **+ Add event handler** .


d. Under **Page-level event handlers**, select **Update client state**
**parameter** .


e. In **Client State Parameter Name**, select **count** .


f. Point to the **New Value** field and select the **Bind data or use**
**scripts** icon.


g. On the **Data types** tab, select **Client states** .


h. Double-click on the **count** pill.


i. Select the **Formulas** tab.


j. In the list, select **Math** .


k. Double-click on the **SUB** pill.


l. In the **right** pill at the top, remove the text and type `1` .


m. Select **Apply** .


n. Select **Add** .


14. Test the counter by selecting **Preview** .


15. Select the up arrow button to increase the count and the down
arrow button to decrease the count.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-719-1.png)


**Result**


You added a button component to increase the count by one and
another button component to decrease the count by one. You added
the stylized text component to show the count as it increased and
decreased.


For detailed, technical information about the button component, see
[Button Overview & API.](https://developer.servicenow.com/dev.do#!/reference/next-experience/washingtondc/now-components/now-button/overview)


For detailed, technical information about the stylized text component,
[see Stylized Text Overview.](https://developer.servicenow.com/dev.do#!/reference/next-experience/washingtondc/now-components/now-stylized-text/overview)


Create and bind a client state parameter value to a component
in UI Builder. By adding custom values to your components, these
components can then be automatically updated through a script.


**Before you begin**


Role required: ui_builder_admin


**About this task**


You can add two components to a page and then connect them by
using client state parameters and scripts. Start by creating a client state
parameter and then binding the client state parameter to one of the
components, such as a label. Next, you create a client script and bind it
to a second component, such as a button, using an event handler. When
you create the event handler, bind the client state parameter value to it
to connect the two components. If you click one component, it changes
the state of the other component. Client states are useful because you
can add custom values to your components that can be automatically
updated through a script. Think of a client state as a bucket for storing
information that is specific to the page.


For example, you can add a button and label component to your page.
The button changes the value of the label, such as changing the text
color.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create or open a page.
For more information, see Manage UI Builder pages and page
variants.


4. Add two components to your page.
For more information, see Add and configure components.


5. To define a client state parameter with an associated value, select
Client state parameters in the lower-left panel.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-721-1.png)


6. Select **+ Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-722-1.png)


7. Enter a name for the client state name, type, and initial value.


The client state supports Strings, Numbers, Boolean, and JSON. For
example, you could enter the name as `dynamic_label_value`, the
type as `String`, and the initial value as `Initial Value` .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-723-1.png)


8. Bind the value of the client state parameter to your component.


a. Select the component that you want to bind the client state
parameter to.


b. Open the configuration panel and select the **Configure** tab.


c. Point to the field that you want to bind data to and select the


dynamic data binding icon ( ).


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-724-1.png)

The data binding modal appears.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-725-1.png)


d. Select **Client states** in the **Data types** tab.


e. Double-click the client script that you want to bind to the
component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-726-1.png)

f. Select **Apply** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-727-1.png)


9. Select **Save** .


10. Bind the client state value to one component and create a script to
connect the second component to the first.


a. In the left pane, select the **+** icon next to **Client scripts** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-728-1.png)


b. Enter a script name that describes the task.
For example, you could enter `Update Label Value` because
that is what you want the script to do.


c. In the Now Code Editor, add your script.


Let's say that you choose an API to call, and the parameters for
the API, such as a state and a value. For example, you could call
the `api.setState`, and include the `dynamic_label_value` as
the first parameter, and a `NEW VALUE` as the second parameter.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-729-1.png)


11. Add an event handler to your second component to call the new
client script that you created.


a. Select the component on your page that you want to bind the
script to.


b. Select the **Events** tab.


c. Select **+ Add a new event handler** .


d. Under the Scripts section of event handlers, select the script that
you created, and select **+** to add it as an event handler for the
component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-730-1.png)


12. Select **Save** .


13. To preview your page and test the components to ensure they’re
connected, select **Preview** .
When you select one component, it should change the state of the
second component. For example, select the **Button** component to
change the **Label value** component text from **Initial Value** to **NEW**
**VALUE** .


**Result**


What you did in this procedure:


**•** Added two components to your page.


**•** Defined a client state parameter that had an initial value.


**•** Bound the client state parameter to the first component.


**•** Created a client script that updates a value that is defined by the
client state parameter.


**•** Created an event handler for the second component to call the new
client script that you just created


**•** Selected the second component so that it changed the state of the
first component.


## **Define and bind client scripts to components**


Add and edit client scripts in UI Builder so that you can update the client
state through events. You can bind these scripts to any component by
using an event handler.


**Before you begin**


Role required: ui_builder_admin


**About this task**


You can create JavaScript client scripts in UI Builder by using the Now
Code editor. Then, you can add the client script as an event handler to
update the client state, emit a handled event of your page, or execute
a data resource operation. For example, you could write a script to
increment a date or counter, and bind the script to a component event,
like a button click. For more information about the Now Code Editor, see
Edit code with the Now Code Editor (advanced feature).


With these scripts, you can do the following actions:


**•** Get available data, manipulate the data, and store it in the client
state.


**•** Access data resource results.


**•** Execute data resource operations.


**•** Dispatch events.


**Procedure**


1. Navigate to **All > Now experience framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
For more information, see Configure how users interact with your
applications in UI Builder.


3. Open or create a page.
For more information about how to create a page in UI Builder, see
Create a page in UI Builder.


4. (Optional) If you do not have any components on your page, add a
component to your page.
For example, you can add a Heading component. For more
information, see Add and configure components.


5. Select **+** next to **Client scripts** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-732-1.png)


6. Name your script.


A descriptive name helps you know what the script does. It also
makes it easier to find the script later when you add it to an event
handler. The following example shows a simple date client script.


7. Write your script to perform an action.


For example, you could write a simple
date script that you bind to a component.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-733-1.png)


8. (Optional) Add a **Script include** or **Associated components**, which
shows up in the `imports` parameter of your client script function.


9. Select the component on your page that you want to bind the script
to and then select **Events** .


10. Select **+Add a new event handler**, select the script that you created
under **Scripts**, and then select **Add** .


The following example shows a date client script.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-734-1.png)


11. Select **Save** .


12. To preview your scripted component, select .

## **Multi-table data configuration**


Present data from multiple tables using components and control the
layout and styling.


A data resource fetches the data that UI Builder uses to display
information in a component. Most often, a component is mapped to
data contained in one table. However, there are numerous use cases
where there’s a need to map a single component to information in
multiple tables, for example:


**•** Place the card component in a repeater and use multi-table data
configuration to pull data from different sources to display on the cards.


**•** Create a portal page that displays a list of tasks pulled from different
locations.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-735-1.png)


**Note:** You can configure more than one multi-table data resource
on a single page to display different sets of data.


**Multi-table data configuration and Entity View Action Mapper**


The Entity View Action Mapper (EVAM) can also be used to configure
cards and lists using different data sources. The EVAM is an option for
users who understand and are comfortable working with JSON. The
multi-table data configuration option gives you greater control over the
presentation of data, makes it easier to configure the data, and enables
you to remain in UI Builder. Use the option that you prefer. For more
information about EVAM, see Work with the Entity View Action Mapper
for UI Builder.


**•** Fetch data from multiple sources


Learn how to obtain data from different sources to use in a single
component.


Learn how to obtain data from different sources to use in a single
component.


**Before you begin**


Role required: ui_builder_admin


**About this task**


Place the card base container component in a repeater and use multitable data configuration to present all active incidents and problems
created in the last two years.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Create a page from scratch.
For more information about how to create a page, see Create a
page in UI Builder.


4. Add a multi-table data resource.


a. In the data shelf, select **+ Add data resource** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-736-1.png)


b. In **Search**, enter `multi-table` .


c. Select **Multi-table data** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-737-1.png)


d. Select **Add** .


5. Configure the first data source.


a. In **Data sources**, select **+ Add** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-737-2.png)


b. In **Table**, enter `incident` and select the **Incident** table.


c. In **Sort field**, enter `number` and select **Number** .


d. In **Name**, enter `Incident` .


e. In **Return fields**, add **Number**, **State**, **Description**, and **Active** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-738-1.png)


f. Select **Edit conditions** .


g. Build the condition **Active is true** .


h. Select **and** .


i. Build the condition **Created on Last 2 years** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-739-1.png)


j. Select **Apply** .


k. Select **Apply** .


6. Configure the second data source.


a. In **Data sources**, select **+ Add** .


b. In **Table**, enter `problem` and select the **Problem** table.


c. In **Sort field**, enter `number` and select **Number** .


d. In **Name**, enter `Problem` .


e. In **Return fields**, add **Number**, **State**, **Description**, and **Active** .
When creating a multi-table data resource, each data source
should have the same return fields specified and in the same
order. This helps ensure that the data displayed on the page is
consistent and accurate.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-740-1.png)


f. Select **Edit conditions** .


g. Build the condition **Active is true** .


h. Select **and** .


i. Build the condition **Created on Last 2 years** .


j. Select **Apply** .


k. Select **Apply** .


l. Select the **X** to close the **Edit Multi-table data** pop-up.


7. Select **Save** .


8. Add the heading component.


a. In the content tree, select **+ Add content** under **Body** .


b. In **Search** enter `heading` .


c. Select the **Heading** component.


d. In the configuration panel, on the **Configure** tab, select **None -**
**Configure the component manually** .


e. In **Label**, delete the default text and enter `Active incidents`

`and problems created in last two years` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-741-1.png)


f. Select **Save** .


9. Add a container.


a. In the content tree, select **+ Add content** under **Heading 1** .


b. On the **Layouts** tab, in the **Advanced** section, select **Flexbox** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-741-2.png)


c. In the configuration panel, on the **Configure** tab, select **None -**
**Configure the component manually** .


d. In **Sizing**, set the **Width** by entering `300` .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-742-1.png)


e. Select **Save** .


10. Add the repeater component.


a. In the content tree, select **+ Add content** under **Container 1** .


b. In **Search** enter `repeater` .


c. Select the **Repeater** component.


d. In the configuration panel, on the **Configure** tab, select **None -**
**Configure the component manually** .


e. Select **Save** .


f. In the configuration panel, on the **Configure** tab, hover over the
**Data array** field and select the bind data icon.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-743-1.png)


g. Under **Data types** select **Data resource** .


h. Select **Multi-table data 1** .


i. Select **output > data > GlideMultiDatasource_Query >**
**getMultiDatasourceData** .


j. Double-click (or use the keyboard shortcut) on the **items** pill.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-743-2.png)


Check that the top section is accurate.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-744-1.png)


k. Select **Apply** .


l. Select **Save** .


11. Add the card base container component within the repeater.


a. In the content tree, select **+ Add content** under **Repeater 1** .


b. Locate and select the **Card Base Container** component.


c. In the configuration panel, on the **Configure** tab, select **None -**
**Configure the component manually** .


d. Select the **Styles** tab.


e. To add a little space around the cards, go to **Spacing**, select
**Margin**, and then select **M** (for medium).


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-745-1.png)


f. Select **Save** .


12. Add the heading component within the card base container.


a. In the content tree, select **+ Add content** under **Card Base**
**Container 1** .


b. Locate and select the **Heading** component.


c. In the configuration panel, on the **Configure** tab, select **None -**
**Configure the component manually** .


d. In the configuration panel, on the **Configure** tab, delete the
default text in **Label** .


e. Point to the **Label** field and select the bind data icon.


f. Under **Data types** select **Repeater** .


g. Select **value > fields** .


h. Select the top pill and in the last column check for **displayValue**
with an incident or problem number.


i. Double-click (or use the keyboard shortcut) on the **displayValue**
pill with an incident or problem number.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-746-1.png)


Check that the top section is accurate.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-746-2.png)


j. Select **Apply** .


k. On the **Configure** tab, select the **Hide bottom margin** option.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-747-1.png)


l. Select **Save** .


13. Add the first stylized text component to show the description of the
incident or problem.


a. In the content tree, point to **Heading 2**, select the menu (three
vertical dots) icon, and select **Add after** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-748-1.png)


b. Locate and select the **Stylized text** component.


c. In the configuration panel, on the **Configure** tab, select **None -**
**Configure the component manually** .


d. In the configuration panel, on the **Configure** tab, delete the
default text in **Text** .


e. Point to the **Text** field and select the bind data icon.


f. Under **Data types** select **Repeater** .


g. Select **value > fields** .


h. Select the third pill in the list and in the last column check that the
**displayValue** contains no information.


i. Double-click (or use the keyboard shortcut) on the **displayValue**
pill with no value.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-749-1.png)


Check that the top section is accurate.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-749-2.png)


j. Select **Apply** .


k. To reduce the text size, go to the **Configure** tab and change the
**HTML tag** to **Paragraph** .


l. Select **Save** .


14. Add the second stylized text component to show the state of the
incident or problem.


a. In the content tree, point to **Stylized text 1**, select the menu
(three vertical dots) icon, and select **Add after** .


b. Locate and select the **Stylized text** component.


c. In the configuration panel, on the **Configure** tab, select **None -**
**Configure the component manually** .


d. In the configuration panel, on the **Configure** tab, delete the
default text in **Text** .


e. Point to the **Text** field and select the bind data icon.


f. Under **Data types** select **Repeater** .


g. Select **value > fields** .


h. Select the second pill in the list and in the last column check
that the **displayValue** contains a state such as **Resolved** or **In**
**Progress** .


i. Double-click (or use the keyboard shortcut) on the **displayValue**
pill with a state value.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-750-1.png)


Check that the top section is accurate.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-750-2.png)


j. Select **Apply** .


k. To reduce the text size, go to the **Configure** tab and change the
**HTML tag** to **Paragraph** .


l. Select **Save** .


15. Select **Preview** .
The page heading is at the top. Each card contains a heading with
the incident or problem number. The cards also show the description
(if one is available) of the incident or problem and the state. Data
is being pulled successfully from two sources: the incident table and
the problem table.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-751-1.png)


16. Select the **X** to close the preview overlay.


## **Work with the Entity View Action Mapper for UI Builder**


With UI Builder, you can use the Entity View Action Mapper (EVAM)
application to standardize how the data sources in your components are
displayed in your cards and lists.


**EVAM Overview**


Entity View Action Mapper (EVAM) is an application that standardizes
how different data sources are displayed in cards and lists. UI Builder uses
EVAM data sources to show information in a component as a card grid
view or as a list of information. You can add a toggle to your component
to let users switch between card grid and list views.


EVAM consists of the following components:


**•** Entity (data source). Associated data that you intend to display, such
as a community post or a user.


**•** View. How a card displays data and actions.


**•** Actions. Action that it performs on the card. For example, you can
activate a user into your system.


**•** Map. A process that maps the data source to generic fields that are
displayed on the card. You can also associate actions that trigger from
the card view.


**EVAM and Multi-table data configuration**


The EVAM is an option for users who understand and are comfortable
working with JSON. The multi-table data configuration option is an
alternative that gives you greater control over the presentation of data,
makes it easier to configure the data, and enables you to remain in UI
Builder. Use the option that you prefer. For more information, see Multitable data configuration.


**EVAM data sources**


You add EVAM data sources in UI Builder and bind them to a
component.


EVAM data resources

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-753-1.png)


**EVAM data sources**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-753-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-754-1.png)


|EVAM data source|Description EVAM Data Resource|
|---|---|
||EVAM Data Resource<br>configuration|
|Fetch EVAM Data|To add an EVAM definition and<br>other information about the data<br>source, select**Configuration**.<br>**•** Type: GRAPHQL.<br>**•** When to evaluate: To have the<br>EVAM data resource instance<br>evaluated on a page load,<br>select**Immediately**. To use an<br>event handler to evaluate the<br>EVAM data resource, select**Only**<br>**when invoked**.<br>**•** EVAM definition: In the**EVAM**<br>**Definition** field, enter the|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-755-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-756-1.png)


|EVAM data source|Description|
|---|---|
|||
|Fetch EVAM Metadata|To select when to evaluate<br>the EVAM data resource and<br>add an EVAM definition, select<br>**Configuration**.<br>**•** Type: GRAPHQL.<br>**•** When to evaluate: To have the<br>EVAM data resource instance<br>evaluated on a page load,<br>select**Immediately**. To use an<br>event handler to evaluate the<br>EVAM data resource, select**Only**<br>**when invoked**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-757-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-758-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-758-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-759-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-760-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-760-1.png)

**•** Add an Entity View Action Mapper data resource to a page


Add an Entity View Action Mapper (EVAM) data resource to your page
in UI Builder so that you can standardize how the data sources in your
components are displayed in your cards and lists.


Add an Entity View Action Mapper (EVAM) data resource to your page
in UI Builder so that you can standardize how the data sources in your
components are displayed in your cards and lists.


**Before you begin**


Role required: ui_builder_admin


**Procedure**


1. Navigate to **All > Now experience framework > UI Builder** .


2. Open an experience to work in or create an experience by selecting
**Create > Experience** .
See Configure how users interact with your applications in UI Builder
for more information on creating experiences.


3. Open or create a page.
For more information, see Manage UI Builder pages and page
variants.


4. (Optional) If you do not have any components on your page, add a
**Data set** component to your page.
For more information, see Add and configure components.


5. In the **Data and scripts** panel, select the **+** icon and then select **Data**

**resource** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-762-1.png)


6. Enter `evam` in the search field.


7. Select the EVAM data resource that you want to add and repeat this
step for all the EVAM data resources for your page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-763-1.png)

8. Configure each EVAM data resource.


**EVAM data sources**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-763-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-764-1.png)


|EVAM data source|Description Configuration pane, preview the|
|---|---|
||Configuration pane, preview the<br>EVAM definition script.<br>EVAM Data Resource<br>configuration|
|Fetch EVAM Data|To add an EVAM definition<br>and other information about<br>the data source, select<br>**Configuration**.<br>**•** Type: GRAPHQL.<br>**•** When to evaluate: To<br>have the EVAM data<br>resource instance evaluated<br>on a page load, select<br>**Immediately**. To use an<br>event handler to evaluate<br>the EVAM data resource,<br>select**Only when invoked**.<br>**•** EVAM definition: In the**EVAM**<br>**Definition** field, add the<br>EVAM definition record that<br>is associated with the data<br>resource.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-765-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-766-1.png)


|EVAM data source|Description|
|---|---|
|||
|Fetch EVAM Metadata|To select when to evaluate<br>the EVAM data resource and<br>add an EVAM definition, select<br>**Configuration**.<br>**•** Type: GRAPHQL.<br>**•** When to evaluate: To<br>have the EVAM data<br>resource instance evaluated<br>on a page load, select<br>**Immediately**. To use an<br>event handler to evaluate|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-767-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-768-1.png)


|EVAM data source|Description|
|---|---|
|||
|Search EVAM Data Resource|To add an EVAM definition<br>and other information about<br>the data source, select<br>**Configuration**.<br>**•** Type: Composite.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-769-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-770-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-771-1.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-772-2.png)


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-772-1.png)

9. Configure your data set component:


**•** Bind an EVAM data resource to your component.


**•** Set the **Show grid/list** toggle to on to let users choose between
the grid or list view of the EVAM information on the page.


**•** Set the other configuration settings for the cards on the page.


10. Select **Save** .


11. View and test your page by selecting the **Preview** button.
Finished state of the EVAM

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-773-1.png)

## Edit code with the Now Code Editor (advanced feature)


Now Code Editor is a rich-text editor like interface that supports
Cascading Style Sheets (CSS), Hypertext Markup Language (HTML),
JavaScript, Extensible Markup Language (XML), and JavaScript Object
Notation (JSON). Use Now Code Editor to modify UI configuration, data
resource configuration, styles, events, client-side and server-side scripts in
Next Experience UI Builder components.


Now Code Editor supports the following features:


**•** Basic editing


**•** Debugging


**•** Command palette


**•** Code formatting


**•** Syntax checking and highlighting


**•** Auto-suggestions


**•** Script macros for common code


**Basic editing**


**Action** **Description**


|Format code|Applies proper indentation to the<br>script.<br>Keyboard shortcut:<br>• Windows: Shift+Alt+F<br>• Mac: Shift+Option+F|
|---|---|
|Highlight syntax|Highlights the syntax of the code.|
|Check syntax|Checks for formatting errors and<br>highlights syntax errors.<br>**•** Windows: Shift+Alt+C<br>**•** Mac: Shit+Option+C|
|Show suggestions|Displays a list of valid elements at<br>the insertion point such as:<br>**•** Class names<br>**•** Function names<br>**•** Object names<br>**•** Variable names<br>Select and click an entry to add it to<br>the script.<br>Keyboard shortcut:|


|Action|Description • Windows: Control+Space|
|---|---|
||**•** Windows: Control+Space<br>**•** Mac: Control+Space<br>You can also enable or turn off<br>**Syntax highlighting** from the**Settings**<br>menu.|
|Toggle comments|Comments one or more lines of<br>code with two consecutive forward-<br>slashes //.<br>Keyboard shortcut:<br>**•** Windows: Control+/<br>**•** Mac: Command+/|
|Show minimap|Displays the minimap of the code<br>snippet.<br>You can display or hide the minimap<br>option, from the**Settings** menu.|
|Enable word wrap|Enables word wrap function in the<br>editor area.<br>You can toggle the**Enable word**<br>**wrap** option from the**Settings** menu.|
|Show command palette|Displays a list of available<br>commands for the common<br>operations. You can execute editor<br>commands, find and replace text,<br>fold and unfold code blocks, toggle<br>comments and many more tasks<br>using the same interactive window.<br>Keyboard shortcut<br>**•** Windows: F1|


**Action** **Description**


|Col1|• Mac: F1|
|---|---|
|Expand editor<br> or collapse<br>editor|Expands or collapses the editor.<br>Keyboard shortcut<br>**•** Windows: Control+M<br>**•** Mac: Control+M|


**Debugging**


To launch Script Debugger, click the Script Debugger icon in the
toolbar.


**Note:** You can add a breakpoint, conditional breakpoint, or
logpoint, only when debugging is enabled and selected language is
JavaScript.


**Task** **Do this**


|Add breakpoint|Right-click beside a line number in the ruler<br>area and select Add breakpoint.|
|---|---|
|Add conditional<br>breakpoint|1. Right-click beside a line number in the<br>ruler area and select**Add conditional**<br>**breakpoint**.<br>2. Enter a break condition in the editor.|
|Add logpoint|Right-click beside a line number in the ruler<br>area and select**Add logpoint**.|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-777-1.png)


**Code editor macros**


**for**


**•** Description: Inserts a standard for loop with an example array.


**•** Output:

```
 for (var i=0; i< myArray.length; i++) {
 //myArray[i];

 }

```

**method**


**•** Description: Inserts an empty JavaScript function template.


**•** Output:

```
 /*______________________________________________________

 ___________
 * Description:
 * Parameters:

 * Returns:

 _____________________________________________________
 ___________*/
 : function() {

 },

```

**info**


**•** Description: Inserts a GlideSystem information message.


**•** Output:

```
 gs.addInfoMessage(gs.getMessage(""));

```

**doc**


**•** Description: Inserts a comment block for describing a function or
parameters.


**•** Output:

```
 /**

 * Description:

 * Parameters:

 * Returns:
 */

```

**vargror**


**•** Description: Inserts a GlideRecord query for two values with an OR
condition.


**•** Output:

```
 var gr = new GlideRecord('');

 var qc = gr.addQuery('field', 'value1');

 qc.addOrCondition('field', 'value2');
 gr.query();

 while (gr.next()) {

 }

```

**vargr**


**•** Description: Inserts a standard GlideRecord query for a single value.


**•** Output:


```
     var gr = new GlideRecord("");
     gr.addQuery("name", "value");
     gr.query();
     if (gr.next()) {

     }

## **Component Builder**

```

Learn how to use Component Builder to assemble reusable components
for your UI Builder pages.


**•** Create custom components to reuse across pages with component
builder


Reuse custom components across experiences and pages in UI Builder.


**•** Enable configuration of components with inherited controllers in
component builder


Learn how components can inherit page resources.

## Create custom components to reuse across pages with component builder


Reuse custom components across experiences and pages in UI Builder.


Create custom components in UI Builder's component building UI. The
component building UI shares many similarities to page building and
enables you to configure components the same way you would when
configuring a page in UI Builder.


**The power of custom components**


Building custom components improves efficiency, consistency, and
maintainability across your experience. By creating reusable UI elements,
you avoid duplicating configurations, ensure a uniform look and feel,
and make it easier to manage updates or design changes. Custom
components also simplify complex layouts, support flexible configurations,
and enable for easier testing and debugging. They’re also helpful
in team environments, where shared components help streamline
collaboration and keep the user experience consistent at scale.


Custom components are especially valuable when designing pages for
different user types within your experience. For example, you can create
a reusable component that includes both a list and a data visualization,
then tailor its content or behavior based on the user group enabling you
to maintain a consistent layout while delivering role-specific information.


Components edited in the Component Builder will automatically update
on all pages where they are used.


**Important:** Custom components created in an instance remain
available only within that instance until they are migrated to other
instances using update sets or application installations.


**Custom components or page collections**


To build efficient, scalable digital experiences, it’s important to reuse
elements wherever possible. Two ways to do this are through custom
components and page collections. Each serves a distinct purpose
depending on the scope of reuse that you need.


**Custom Components**


Use custom components when you want to replicate a specific part of a
page like a heading, list, form, or buttons across multiple pages.


You want to apply a consistent theme or configuration to a component
or group of components.


You're designing pages to be modular or flexible where parts of a page
may change but shared components remain consistent.


You want to manage changes in one place and have them updated
everywhere the component is used.


Multiple teams are simultaneously working on different sections of the

same page.


**Page Collections**


You want to reuse an entire page layout and configuration across
multiple pages or experiences.


You must build a variation of full pages for different users or workflows.


You want to use a set of tabs across multiple pages or experiences.


**Custom component UI**


You can access the component builder in UI Builder by selecting **Create**
in the header or the **Component** tile on the UI Builder home page.


UI Builder home page

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-781-1.png)


Component Builder UI

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-782-1.png)


Components built with UI Builder can be found in the toolbox when
adding a component to a page and in the component list on the home
page of UI Builder. You can update or modify custom components by
locating it in the components list on the home page of UI Builder.


Component List

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-783-1.png)


You can quickly duplicate a custom component from the component
settings screen by selecting **Duplicate**, which creates an exact copy of
the component for reuse or modification.


Custom Component Settings

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-784-1.png)


**Component Builder vs NOW CLI Component Development**


There are two ways to build components for UI Builder. The first is using
the low-code component within UI Builder, which offers a drag-and-drop
[interface for creating custom components. The second is using NOW](https://developer.servicenow.com/dev.do#!/reference/next-experience/yokohama/cli/getting-started)
[CLI developer tools to build components through code. Both methods](https://developer.servicenow.com/dev.do#!/reference/next-experience/yokohama/cli/getting-started)
produce components that can be added to the UIB toolbox and reused
across experiences. Keep in mind that changes to included components
may impact both types.


Although both tools create components for UI Builder, there are
important differences to consider.


Component Builder in UI Builder:


**•** Components built within UI Builder can reference controllers and data

resources.


**•** Creates "Macroponent Components," which are stored in the
sys_ux_macroponent table.


**•** Component Builder is ideal for users who prefer a visual, drag-and-drop
interface for building components.


**•** Great for quickly creating simple to moderately complex components.


NOW CLI components:


**•** Intended for developers who need to write custom HTML, CSS, and
JavaScript.


**•** Suitable for building complex and customizable components.


**•** Components created with NOW CLI are stored in the
sys_uib_toolbox_component table.


**Best practices**


The UI Builder custom component builder lacks governance capabilities
and can lead to duplication and inconsistency in your experience.
Teams may create similar components with slight variations, resulting in
a fragmented UI, and confusing user experience. It is recommended that
your team completes regular audits and cross-team communication to
maintain alignment and avoid fragmentation as your experiences grows.


All components are designed to be upgrade safe, as long as their
security policy is set to read_only. This provides greater upgrade
protection for larger components or page partials compared to other
deployable units like bundles and page templates. However, this also
means that out-of-the-box (OOTB) components may not be editable.


**Create components to reuse across pages**


Build reusable custom components to use across experiences and pages
in UI Builder.


**Before you begin**


Role required: ui_builder_admin


**About this task**


In this Component Builder example, we will create a stopwatch
component to track elapsed time, which can be added to any
page. The component will include customizable properties that can be
modified once it's placed onto a page.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Select **Create** from the UI Builder home page.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-787-1.png)

3. Select **Component** .


4. In the form, fill in the fields.


Create a component dialog box

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-788-1.png)


**Create a component form**


|Field|Description|
|---|---|
|Name|Add a name to track your<br>component internally. The<br>component name appears in<br>the toolbox. For this example, it<br>is`Stopwatch`.|
|Categories|Add a category to your<br>component to help easily find it<br>in the toolbox. You can update<br>the category later in the Settings.<br>For this example select**Content**.|


|Field|Description|
|---|---|
|Description|Add description to describe<br>when and how to use your<br>component.|
|Icon|Select an icon to represent the<br>component in the toolbox.|


5. Select **Create** .
The page opens in Component Builder view.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-790-1.png)


6. Add a custom component property by selecting **+ Add property** in
the **Properties and policy** section.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-791-1.png)


a. Select **String** from the list.


b. Enter the following values in the configuration panel.


**Component properties**


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-791-2.png)


**Field** **Value**

|Property ID|svgImageSource|
|---|---|
|Default value|`animateddino.svg`|


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-792-1.png)


c. Select **Save** .


7. Configure the layout for the custom component by selecting the **+**
**Add Content** button.


a. Select **Single column**, then select **Add** .


b. In the content tree, under **Column 1**, select **+Add content** .


c. Select **Card Base Container**, then select **Add** .


d. In the content tree, under **Card Base Container 1**, select **+ Add**

**content** .


e. Select **Layouts** .


f. Select **Flexbox**, then select **Add** .


g. Select **Save** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-793-1.png)


8. Add a stylized text component in our Flexbox container by selecting
**+ Add content** under **Container 1** .


a. Select the **Stylized text** component, then select **Add** .


b. Select **Cancel** to close the preset window.


c. Select **Save** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-794-1.png)


9. To configure the stylized text component we will add some client
state parameters.


a. Select **Client state parameters** in the **Data and scripts** section.


b. In the **Edit client state parameters** dialog, enter the following
values:


**Client state parameters**


**Name** **Type** **Initial value**

|startTime|Number|Col3|
|---|---|---|
|elapsedTime|String|00:00:00|
|timeinterval|JSON||
|stopwatchRunning|Boolean||


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-795-1.png)


c. Select **Apply** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-795-2.png)


d. Select **Save** .


10. To configure the stylized text component we are going to bind the
**elapsedTime** client state parameter.


a. Select the **Stylized text 1** component in the content tree.


b. Select the bind icon when pointing to the **Text** field of the stylized
text component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-796-1.png)

c. Select **Client states** .


d. Double-click the **elapsedTime** pill.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-797-1.png)


e. Select **Apply** .


f. Select **Save** .


11. Add a Flexbox container to hold the buttons.


a. Select the **+** icon under the stylized text component.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-798-1.png)


b. Select **Layouts** .


c. Select **Flexbox** .


d. Select **Add** .


12. Add and configure the stopwatch running renderer and the start
button.


a. Select **+ Add content** in the container you added in the previous
step and add a **Conditional renderer** .


b. Select **+ Add condition** in the content tree.


c. Select **Single component**, then select **Next** .


d. Select **Button iconic**, then select **Next** .


e. In the **Edit settings** dialog, enter the following values:


**•** Component label: `Start`


**•** Component ID: `start_button`


**•** Render content: **Always**


f. Select **Apply** .


g. Select the **Start** button in the content tree.


h. Set the following properties in the configuration panel.


**Component properties**


**Field** **Value**

|Icon|stopwatch-fill|
|---|---|
|Variant|**Primary**|
|Size|**Large**|
|Tooltip text|`Start`|


i. Select **Save** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-800-1.png)


13. Configure the stop button to display while the stopwatch is running.


a. Select **+ Add condition** in the content tree.


b. Select **Empty container**, then select **Next** .


c. In the **Edit settings** dialog, enter the following values:


**•** Component label: `Running`


**•** Component ID: `running_container`


**•** Render content: **When condition below is true**


d. Select the bind icon while pointing at the **Condition** field.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-801-1.png)


e. Select **Client states**, then double-click the **stopwatchRunning** pill.


f. Select **Apply** .


g. Select **Apply** .


h. Select **+ Add content** in the **Running** container and add a **Button**
**iconic** .


i. Select **Button iconic 1** in the configuration panel and enter the
following values:


**•** Component label: `Stop`


**•** Component ID: `stop_button`


j. Select **Apply** .


k. Set the following properties in the configuration panel.


**Component properties**


**Field** **Value**

|Icon|stopwatch-fill|
|---|---|
|Variant|**Secondary**|
|Size|**Large**|
|Tooltip text|`Stop`|


l. Select **Save** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-803-1.png)


14. Reorder the conditions so that **Running** appears above **Start** .


a. Select **Conditional renderer 1** in the content tree.


b. In the configuration panel, select and drag the drag handle icon


to move the conditions into position.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-804-1.png)


Conditions are evaluated in order from top to bottom, so **Running**
must appear above **Start** for the buttons to display correctly.


15. Add the logic for the component by selecting **+** next to **Client scripts**
in the **Data and scripts** section.


a. Enter `Start` in the **Script name** field.


b. Paste the following script into the script field.

```
   function handler({ api, helpers }) {
   console.log('Start script running');

   if (api.state.stopwatchRunning === undefined) {
   api.setState('stopwatchRunning', false);
   api.setState('elapsedTime', '00:00:00');
   api.setState('startTime', null);
   api.setState('intervalId', null);
   }

   let running = api.state.stopwatchRunning;

   function pad(n) {
   return n < 10 ? '0' + n : n.toString();
   }

   function updateElapsedTime(startTime) {
   if (!running) {
   if (api.state.intervalId) {
   helpers.timing.clearInterval(api.state.inte
   rvalId);
   api.setState('intervalId', null);
   console.log('Interval cleared');
   }
   return;
   }

   if (!startTime) {
   console.log('No startTime passed to updateEla
   psedTime, cannot update');
   return;
   }

   const now = Date.now();
   const elapsedMs = now - startTime;

   const totalS
             econds = Math.floor(elapsedMs / 1000
   );
   const hours = pad(Math.floor(totalSeconds / 3600
   ));

```


```
                            Seconds % 3
   const minutes = pad(Math.floor((total
   600) / 60));
   const seconds = pad(totalSeconds % 60);

   const formattedTime = `${hours}:${minutes}:${se
   conds}`;

   console.log('Setting elapsedTime:', formattedTi
   me);
   api.setState('elapsedTime', formattedTime);
   }

   if (!running) {
   const now = Date.now();

   api.setState('startTime', now);
   api.setState('elapsedTime', '00:00:00');
   api.setState('stopwatchRunning', true);
   running = true;

   if (api.state.intervalId) {
   helpers.timing.clearInterval(api.state.interv
   alId);
   api.setState('intervalId', null);
   console.log('Existing interval cleared befor
   e starting new one');
   }

   // Pass startTime directly here
   updateElapsedTime(now);

   const id = helpers.timing.setInterval(() => {
   updateElapsedTime(now);
   }, 1000);
   api.setState('intervalId', id);
   console.log('Interval started with id:', id);
   } else {
   if (!api.state.intervalId) {
   // Use existing startTime from state, but be
   mindful it might still lag
   const storedStartTime = api.state.startTime |
   | Date.now();
   const id = helpers.timing.setInterval(() => {
   updateElapsedTime(storedStartTime);

```


```
   }, 1000);
   api.setState('intervalId', id);
   console.log('Interval restarted with id:', id
   );
   }
   }
   }

```

c. Select **Apply** .

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-807-1.png)


d. Select **+** next to **Client scripts** to add a second script.


e. Enter `Stop` in the **Script name** field.


f. Paste the following script into the script field.

```
    function handler({ api, helpers }) {
    console.log('Stop script running');

    if (api.state.stopwatchRunning === undefined) {
    // If state is not initialized yet, initialize
    it to avoid errors
    api.setState('stopwatchRunning', false);
    api.setState('elapsedTime', '00:00:00');
    api.setState('startTime', 0);
    api.setState('intervalId', null);
    }

    if (api.state.stopwatchRunning) {
    api.setState('stopwatchRunning', false);
    if (api.state.intervalId) {
    helpers.timing.clearInterval(api.state.interv
    alId);
    api.setState('intervalId', null);
    }
    }
    }

```

g. Select **Apply** .


h. Select **Save** .


16. Add event handlers to the buttons we created in the previous steps.


a. Select the **Start** button in the content tree and open the **Events**
tab in the configuration panel.


b. Select **Add handler** under **Button iconic clicked**, then select the
**Start** client script we created in the previous steps.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-809-1.png)


c. Select **Continue**, then select **Add** .


d. Select the **Stop** button in the content tree and open the **Events**
tab in the configuration panel.


e. Select **Add handler**, then select the **Stop** client script we created
in the previous steps.


f. Select **Continue**, then select **Add** .


g. Select **Save** .


17. Select **Preview** to test the configured components.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-810-1.png)


**Result**


Your custom component is now available in the UI Builder toolbox.

## Enable configuration of components with inherited controllers in component builder


Learn how components can inherit page resources.


Using component builder, developers add data resources in two ways:
directly within the component or through inheritance from the page.


**Direct configuration**


When you add data resources directly to a component, they remain
contained within that component. These internal data resources are not
visible or accessible when the component is placed on a page.


**Inheritance**


You can configure a component to inherit data resources from the page
where it's placed. When inheritance is enabled, the component scans
for data resources of the same type and automatically connects to
them. For example, a component configured to inherit form controllers
will look for form controllers on the page. This allows the component to be
used across different page contexts and leverage existing data resources
without manual configuration each time.


When you place a component configured for inheritance on a page, the
inheritance behavior works as follows:


**Matching**
**Behavior**
**resources found**

|No match found|Creates a new resource of the same type using the<br>component's initial configuration|
|---|---|
|One|Connects to that resource|
|Multiple|Connects to the first instance of that resource|


**Enable configuration of components with inherited controllers**


Configure components to automatically inherit controllers and data
resources when placed on pages.


**Before you begin**


Role required: ui_builder_admin


**About this task**


In this Component Builder example, we will create a text component and
configure it to inherit the List controller. We will then place it on an list


page where the component connects to the List controller and displays
the appropriate table name.


**Procedure**


1. Navigate to **All > Now Experience Framework > UI Builder** .


2. Select **Create** from the UI Builder home page.

![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-812-1.png)


3. Select **Component** .


4. In the form, enter the following values:


**Component properties**


**Field** **Value**


|Name|Table Reference|
|---|---|
|Categories|**Content**|
|Description|`Text component that`<br>`displays the name of the`<br>`current page's table`|
|Icon|(Default)|


5. Select **Create** .


6. Add a data resource to the component.


a. In the data resource drawer, select **+ Add data resource** .


b. On the left, select **List Controller** .


c. On the right, select **Advanced configurations** to expand the
section.


d. Select the **Inherit configurations from parent** option to enable the
property.


e. Select **Add** .


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-814-1.png)

7. Create the component.


a. In the content tree, select **+ Add content** .


b. Select **Single column**, then select **Add** .


c. In the content tree, select **+ Add content** under **Column 1** .


d. Select a **Stylized text**, then select **Add** .


e. Select **Cancel** to close the preset window.


8. Configure the component to use the List controller.


a. In the configuration panel, hover over **Text** and select the bind


data icon.


b. On the left, select the **Formulas** tab, then double-click **CONCAT** .


c. In the upper section, double-click **value1** to edit the field and
enter `"List showing records from "` .


d. Double-click **values** to edit the field and enter

`@data.list_controller_1.tableLabel` .


e. Select **Apply** .


9. Select **Save** to save your work.
Your custom component is now available in the toolbox and ready
for use in a page.


10. Place the component on a list page to see it automatically inherit the
List controller and display the table name.


![](https://raw.githubusercontent.com/therealatreides/sn_docs/refs/heads/main/UIBuilder/images/UIBuilder.pdf-816-1.png)


