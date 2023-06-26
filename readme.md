			Continuous Scheduler Improvement

I. Main Features of Minimum Viable Product
	A. Input Categories and Priority
	B. Configure Workload
	C. Summarize Workload Projection
	D. Construct Workload for the Day
	E. Kepp Track of Progress for the Day
	F. Start the Next Day with Updates



II. Feature Descriptions
	A. Input Categories and Priority
		1.Allow users to input
			a.name
			b.category (school, fitness, work, kids...)
			c.credits/length
			d.priority (difficulty, mastery, no. of assignments, or interest based)

	B. Configure Workload
		1. no. of hours required per week
			a.rule of thumb for classes -> 3hrs/credit
			b.based on difficulty
			c.based on mastery
			d.user interest
		2. no. of days/week for working
			a.in order to allow flexibility of few days of the week or spread it out
			  over entire week
		3. no. of houres required per work day
			a.there can be a limit of max 12 hrs, then we'll need to adjust
			b.calculated from 2 previous bullets
			c.this will allow to determine the scheduling part of the day

	C. Summarize Workload Projection
		1. in tabular format list out
			a.tasks
			b.total hours required
			c.working days
			d.hours/working day
			e.3 or 7 day schedule

	D. Construct Workload for the Day
		1. Algorithm to account for no. of tasks and hours required
		2. look into Operating Systems course for algorithms we learned

	E. Kepp Track of Progress for the Day
		1. Ideally have a timer countdown displayed
		2. Allow user to start and record finishing the tasks block
		3. Thus keep record in some Data Structure to access and update

	F. Start the Next Day with Updates
		1. Next day schedule will reflect accomplishments and setbacks
		   so if a tasks block wasn't completed and is high priority it should be included
		   in the next day and bump out lowest priority for the day




III. Future Features
	A. Allow task to be set to a static date and/or time
	B. Visuals such as a pie chart and graphs
	C. Add or remove category at the start of new day
