1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
    - Within a GitHub Action that runs whenever code is pushed because you get immediate and consistent feedback, catch bugs early, block merges on test failures.
2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
    - No
3) What is the difference between navigation and snapshot mode?
    - Navigation opens the browser, loads the page, and time everything that happens during that load. Snapshot looks at the page exactly as it is right at the at the moment, checks stuff like accessibility, best practices, and SEO without realoding and doesn't measure the full load performance.
4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
    - Properly size images to eliminate unnecessary bytes and speed up loading.
    - Reduce unused JavaScript to cut down on main‑thread work
    - Add a <meta name="viewport" content="width=device-width, initial-scale=1"> tag in <head> so the site scales correctly on mobile devices and satisfies Best Practices

 



