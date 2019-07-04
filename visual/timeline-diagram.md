# Timeline Chart

A timeline chart is a chart that visualises events in choronological order. The chart consist of a line that can be either vertical or horizontal, the
events are positioned in the order of occurance along the line with an associated marker. A title indicating the time of ouccrance and a description is
present for every event. It is best suited to track time based events when the data is in categorical format.
The chart is useful for project planning, advertising campaigns, historical events, ect. 

## Bindings

There are two required data bindings to produce the timeline as shown below:

![binding](/images/timeline-diagram/bindingsimg.png)

### Time
Selects the time for every event from the data. Example: March 2018

### Description
Produces the description for the event. Example: Meeting with John from Accounting

## Fitting to container
The chart automatically fits to the container, so chart height and width need not be specified. The user is also able to add as many events to the timeline
as disired and it will automatically adjust to display the chart. To avoid making the text unreadable when the container is made too small, the chart utilises
a scroll bar so the user can scroll through the chart.

## Data incompatibilty and limitations

The timeline outputs the data as text and therefore any data that is added will be displayed. In case of missing entries in the description, the entry that is missing
will appear as undefined. This means that the user should be able to easily spot the missing values for correction.

![latin](/images/timeline-diagram/latincharacters.png)

Limitations include using Latin characters as it may not render correctly as shown above due to GIANT being unable to render the characters when the data is uploaded. As such the user
should avoid using such text characters. Alphanumeric characters and special characters are all supported.

## Use cases

The following is an example use case in which the progress can be tracked for a company project. From the timeline, it can be seen what and when the events take place. As the project progresses more events can be added. At the end of the project, the full timeline will be visible.

![usecase](/images/timeline-diagram/usecaseimg.png)
