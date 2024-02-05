# Heavy Data Processing with Web Workers

## Description

This webpage demonstrates the performance benefits of using Web Workers to handle heavy data processing tasks in a single-page web application. It show the execution time of a data processing task (sorting a large array) with and without using Web Workers.

## Instructions to Run

1. Clone this repository to your local machine.
2. Open `index.html` in a web browser.
3. Click on any of the two buttons (Process with.../Process without...) to start data processing.
4. You can use the third button to check if the main thread (UI thread) is still working/accessible while processing.
5. Observe the performance results displayed on the web page.

## Findings

While the processing is done without web workers the main thread become irresponsive. but when the processing is done with the web workers. On clicking the check button we can see that the UI thread is still responsive hence proving that the processing is done asynchronously.


## References and Resources
https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers

