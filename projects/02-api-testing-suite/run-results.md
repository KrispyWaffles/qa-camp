# API Test Results — JSONPlaceholder

## TEST-001
**Method:** GET  
**Endpoint:** /posts/1  
**Expected:** Status 200, response ID matches requested ID  
**Actual:** Status 200, id=1 matches request  
**Status:** PASS


## TEST-002
**Method:** GET  
**Endpoint:** /posts/9999  
**Expected:** Status 404, empty or error response  
**Actual:** Status 404, body returned {}  
**Status:** PASS


## TEST-003
**Method:** GET  
**Endpoint:** /posts?userId=1  
**Expected:** Status 200, array of posts all with userId=1  
**Actual:** Status 200, returned 10 posts all with userId=1  
**Status:** PASS