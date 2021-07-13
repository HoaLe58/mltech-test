# Mltech test
## How to submit your result
- Please select only `one` of these below tests.
- Create a new branch with this format `<test_no>_<your_name>` for committing your code and your document.
- Your submission must included the guideline, your design or document how to run your code.
- Create a new Pull request whenever you finish your submission.
## Tests
**1. (Web developer) Design and write a simple web application with these requirements (backend or frontend):**
- You can choose the web framework you are good at. (Backend, frontend)
- Database (one of these NoSQL databases): MongoDB, CouchDB, CouchBase, Cassandra, HBase, Redis, Riak, Neo4J
- You can use any resources or 3rd libraries.
- Application:
    - Each user has their own balance and it must be displayed in realtime.
    - User can create an auction (min price, expired time).
    - User can bid that auction. (Each user can bid multiple time to single auction - Update balances)
    - Notify the highest bidder and highest bid when the expired time is reached to all participants and owner. (Update balances)

**2. (Automation tester) Plan and implement business related testcases:**
- Use this test framework: Mocha 
- API references: https://api.mathjs.org/
- `Assume` that this website https://www.online-calculator.com/ using RESTful API from the link above.
- Plan and write your tests based on the user input (click calculator btn) and the response which should be display on the calculator screen (response from those endpoints).
