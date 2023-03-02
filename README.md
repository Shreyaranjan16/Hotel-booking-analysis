# Hotel-booking-analysis
Abstract: 

The Internet is a true gold mine of data. E-commerce and review sites are brimming with a lot of  untapped data with a prominent potential to convert into meaningful insights that can help with robust decision making.
In this case Clients of different applications based on different categories are trying to get some basic and useful insights in order to get better Customer Engagement and its success. We are provided with useful datasets:Hotel Booking.By doing Exploratory Data Analysis (EDA), we can explore, visualize and understand the given  variables in our datasets that are affecting the most in achieving success of  Hotel Booking analysis.

1. Problem Statement:
   Mishandled Reservations and Double Bookings:
   A nightmare scenario for any hotel manager, the double-booked room or mishandled reservation is a tough but sometimes unavoidable part of the job. A well-trained staff is more likely to prevent booking errors, but every now and then, one might slip through. So what do you do when a guest shows up and you don’t have a room available for them?
To proactively prevent these types of administrative errors, you’ll want to invest in a robust property management system (PMS). For instance, RoomKeyPMS gives you a powerful tool to manage bookings with ease. It’s easy-to-use interface helps staff cut down on entry errors. Or, if a last-minute change needs to be made, the system makes it easy to adjust — and also updates in real-time.However, if the damage is already done, here is how you can gracefully manage a missing reservation.After you or a staff member has sincerely apologized, immediately find a room for your guest. If you only have large suites remaining and they were looking for a small single, give them the suite at no extra charge. Try not to offer them a room with less space, unless absolutely necessary. In that case, provide a generous rate reduction. This is a brand-building moment—don’t worry about a few dollars.If your hotel is full, offer to book a room in a sister hotel (if in the same city) or nearby accommodations. Arrange transportation to bring them there, and provide a discounted room at your hotel for the next night. To avoid repeating this problem, you can use a property management system that allows employees to track bookings in a much 
Incorrect Guest Preferences:
You’ve incorrectly assigned a guest to a non-smoking room when they asked for smoking. Or you’ve booked a highly allergic guest on a pet-friendly floor. Incorrect data can put a great amount of stress on both your customer and your front desk agent or manager.
To handle these mistakes, all managers and staff should be well-trained in conflict resolution and customer communication. No matter the complaint, a hotel staff member should always listen, apologize and thank the guest for sharing feedback. Your hotel should have clear policies on who has the authority to resolve which complaints (e.g. can all front desk staff grant refunds and discounts or must they escalate the complaint to a senior manager?). You should also establish guidelines for all major common complaint situations so that every member of your staff understands what to do in case they encounter a problem.
Third-Party Scams:
If you’ve had the unfortunate experience of greeting a guest who thought they had a reservation but had inadvertently been victim to a scam on an illegitimate booking site, you know how unsettling this can be.As a regular habit, monitor news and industry sites for word of these scams. Where appropriate, alert staff and customers if these illegal sites have targeted your region. For a guest who may have had their personal details exposed, contact the authorities and offer to book them a room if you have space available. If you don’t, follow the steps above for a double booking. Treat this guest with compassion and be as helpful as you can.When visitors arrive and what they expected doesn’t match what you’re offering, try to accommodate them as best you can. Be calm, courteous and creative.By preparing ahead of time for any misunderstandings, you’ll be able to resolve customer complaints in a neat and satisfactory manner.
2. INTRODUCTION:

Hotel Booking System is an online booking engine that allows guests to make secure online reservations through hotel websites and helps hotels to accept bookings and collect payments online
Hotel Booking System is a complete hotel quotation booking system that comes with the key role of Hotel XML IN, Hotel XML Out, Hotel Channel Manager, Hotel Extranet and Own Contracting to help hotels to automate day-to-day hotel operations and increase bookings.
3. STEPS INVOLVED:
Importing datasets: Imported both the datasets from google drive to google colab notebook
Manipulating datasets: Deletion and rearrangement has been done in this part, deleted columns like android version and current version. Because of not being considered in the analysis.

Null values Treatment: 
Both the dataset specially User Reviews data contains a large number of null values. In the User Reviews data set, most of the columns contain the same null values so we dropped the observations corresponding to null values. In the Play Store dataset, the Rating column has the maximum null values so we imputed them with the median value of the column. Other null values in columns were dropped accordingly.

Exploratory Data Analysis: 
After importing datasets, did some exploring, deletion of columns and treated null values of different columns. After that, we compared each feature individually and together to get a better understanding and inferences from them




Univariate Analysis: 
Uni means one and variate means variable, so in univariate analysis,there is only one dependable variable. The objective of univariate analysis is to derive the data, define and summarize it, and analyze the pattern present in it. In a dataset, it explores each variable separately. It is possible for two kinds of variables- Categorical and Numerical.
Count Plot: Using count plot we can get the count of different variables where we can easily compare the different categories among themselves.
Pie Chart: To get the population percentage of different variables for e.g. (Type variable), by using pie-chart we get the idea that how many percentages of the total population of the applications are free or paid?
Histogram: A histogram provides a visual representation of the distribution of a dataset: location, spread and skewness of the data; it also helps to visualize whether the distribution is symmetric or skewed left or right. We used the histogram on features like ‘Size’, ‘Rating’ etc.
Distplot:  The distplot represents the univariate distribution of data i.e. data distribution of a variable against the density distribution. The seaborn. distplot() function accepts the data variable as an argument and returns the plot with the density distribution
Bivariate Analysis: 
Here two or more than two variables are being considered for the analysis. We can get the relationship between two variables and are they dependent on each other or not. This definitely gave us a vivid and meaningful image.
Bar plot: We analyzed here categorical data to numerical data and our main purpose is to get the categorical features concerning some numerical features. This graph gives us a better understanding between two variables.
Joint plot: Our main aim of using this graph because this shows better fluctuation on one numerical feature with others. With a single at it we can easily understand the fluctuation and get a better insight.


Heatmap: A heat map is data analysis software that uses color the way a bar graph uses height and width: as a data visualization tool. We applied heatmap to find out the correlation between numerical features, it always gives us a better relationship between 


4. Conclusion: 
That’s it we have reached at the end of our exercise. Firstly, we imported our datasets, did some data wrangling, imputation of null values and finally, we did exploratory data analysis in two parts: Univariate analysis and Bivariate analysis in which we used different types of graphs to get better understanding and to reach at a better result.
We’ve concluded reviews, ratings, size, number of installs and sentiments are the key factor of app engagement and its success. Reviews have a huge impact on rating and also high rated apps have a high number of downloads; small size apps are being downloaded the most.
