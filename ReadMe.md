# Message Broadcast Code Challenge

Hello and welcome!

Thank you for taking the time to interview with us, we are very excited you've made it to the technical challenge! The purpose of this challenge isn't to try to trick your or stump you, and certainly not to waste your time. We're hoping that this will be an opportunity to gain some insight to your approach to NodeJS development. We'll be looking for how you organize your code, how you document or comment it, and what approaches you take to performing the requested processes. We hope this process shouldn't take more than an hour of your time.

So, with that in mind we look forward to seeing your submission!

## Prompt

Create an ExpressJS server that listens to `PORT 8080` for a post API to `/v1/arrayOps/{operator}` that performs the "operator" on an array passed in as the post's body and return an object with the following key/values:

1. A descending sorted version of the input array as `"sorted_input"`
2. The result of the array when processed sequentially by the operator as `"result"`
3. Find the numbers which are greater than average of original array as `"greater_than_average"`

This API should support: `add`, `subtract`, `multiply`, and `divide` and be provided with:

- basic payload validation
- error handling
- appropriate unit tests

For instance `/v1/arrayOps/add` with post data of `{ array: [4,1,5,2,3] }`should return:

```javascript
{
  sorted_input: [5,4,3,2,1],
  result: 15,
  greater_than_average: [5,4]
}
```

Finally, the answer should be posted to a public version control repository like GitHub or GitLab. Please provide us with the link and we will review the code!

Thank you for your time and good luck!