#### Case Study Project - Wheelchair Ramps

National Accessibility currently installs wheelchair ramps for office buildings and schools.
However, the marketing manager wants the company to start installing ramps for event
venues as well. According to a new survey, approximately 40% of event venues are not
wheelchair accessible. However, it is not easy to know whether a venue already has a ramp
installed.
The marketing manager would like to know whether you can develop a model to predict
whether an event venue has a wheelchair ramp. To help you with this, he has provided you
with a dataset of London venues. This data includes whether the venue has a ramp.
It is a waste of time to contact venues that already have a ramp installed, and it also looks
bad for the company. Therefore, it is especially important to exclude locations that already
have a ramp. Ideally, at least two-thirds of venues predicted to be without a ramp should not
have a ramp.
You will need to present your findings in two formats:
1. First, you will need to present your findings to the marketing manager via a 10 minute
oral presentation. The owner has no technical data science background.
2. You will also need to submit a technical report to your manager, who does have a
strong technical data science background.
For details on how your report and presentation will be graded, you can refer to the grading
rubric. You can find more information about the case study in our general information guide.
1
Data
The data is available in a DataCamp Workspace, which you can find from the certification
dashboard. The data set has the following columns:
Column Name Details
venue_name Character, name of the venue.
Loud music / events Character, whether the venue hosts loud events (True) or
not (False).
Venue provides alcohol Numeric, whether the venue provides alcohol (1) or not (0).
Wi-Fi Character, whether the venue provides wi-fi (True) or not
(False).
supervenue Character, whether the venue qualifies as a supervenue
(True) or not (False).
U-Shaped_max Numeric, the total capacity of the u-shaped portion of the
theatre.
max_standing Numeric, the total standing capacity of the venue.
Theatre_max Numeric, the total capacity of the theatre.
Promoted / ticketed events Character, whether the venue hosts promoted/ticket
events (True) or not (False).
Wheelchair accessible Character, whether the venue is wheelchair accessible
(True) or not (False).
