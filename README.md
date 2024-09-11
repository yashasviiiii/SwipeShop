# SwipeShop
This is a shopping website which has a special swipe feature which allows you to right swipe the items you like and left swipe the items you dislike. This offers a gamified experience to user and is targetting the GEN-Z audience.
● OBJECTIVE:  
Creating an interface which will personalise the shopping experience, prompting you to swipe left and right on clothing. This is based on a dating app-esque algorithm where people will be able to swipe right onto the item they like and swipe left to the others. The swipe will bring a “fun interaction” , hence creating a more personalised 
experience. This game-like element is designed to almost make people feel rewarded and increase user engagement and retention.
● APPROACH:
● Collecting fashion products dataset(eg. Myntra’s dataset). This can be done by:
 ○ Web Scraping: Using a tool like BeautifulSoup to scrape product data from 
 myntra website. Looking for articles, images, and descriptions of recent trends.
 ○ APIs: Check if Myntra provides an API for accessing their content 
programmatically.
● Preparing the collected data for our ML model. This will be done in 2 steps:
 a.  Firstly, cleaning the data to remove any unnecessary information.
 b.  Secondly, extracting features like trend names, images, and any other 
relevant attributes.
STEP BY STEP GUIDE INTO THE FUNCTIONING OF THE WEBSITE: 
● Creating the user interface where users can swipe right to like and left to dislike:
 ○ . FrontEnd development using HTML, CSS, and JavaScript to build the interface.
 ○ BackEnd development to set up a backend server using Node.js to handle user interactions and data 
storage.
● Developing a machine learning model to recommend trends based on user preferences:
 ○ Data Storage: Store user interactions (swipes) in a database.
 ○ Model Training: Use collaborative filtering and content-based filtering to build a 
recommendation system. Collaborative filtering can use user interactions to 
recommend similar trends, while content-based filtering can use trend features to find 
similar items.
 ○ Model Updating: Continuously update the model with new user interactions to 
improve recommendations.
● Integrating the machine learning model with our interface using a backend 
framework such as Flask.
● Testing the entire system thoroughly before deploying:
 ○ User Testing: Get feedback from a small group of users to refine the interface 
and recommendation system.
 ○ Deployment: Deploy your application using cloud services like AWS.
 
As we embark on designing our shopping website with a swipe-based interface for fashion 
styles, it's crucial to highlight the myriad advantages this approach brings. This innovative 
interface promises to revolutionize how customers discover and interact with fashion. Now 
that we've explored the innovative technology behind our project, let's focus on the benefits it 
brings to the user experience.

BENEFITS:
● Users often enjoy interactive and gamified experiences. By 
incorporating a swipe interface, we can make the process of browsing 
through clothing styles more engaging and enjoyable.
● The swipe-based interaction gathers valuable data on user preferences. 
This data allows us to tailor recommendations more accurately to each 
user's taste, enhancing satisfaction and increasing the likelihood of 
purchases.
● Analyzing the data (feedback from the swipes)  helps understand trends, 
preferences, and customer behavior, informing merchandising decisions 
and marketing strategies. It helps to understand which kind of clothing 
requires more production hence prevents understocking or 
overstocking and reduces the wastage of raw materials.
● When faced with numerous options, users can experience decision fatigue. The swipe interface 
simplifies decision-making by presenting items one at a time, streamlining the browsing experience.
● A well-executed swipe interface can be a fun feature that encourages users to share their experiences 
on social media. This potential for viral sharing can increase brand visibility and attract new users.
● Through continuous analysis of user interaction and feedback, we 
can refine the recommendation algorithm. This iterative 
improvement leads to a deeper understanding of user preferences 
and better recommendations over time.
● The swipe interface allows for quick adaptation to seasonal 
trends and fashion changes. This flexibility ensures that users are 
always presented with relevant and current styles
