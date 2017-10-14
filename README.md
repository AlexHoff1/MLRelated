This directory is to hold my ML testing code so I can learn how to create good models.

What I know so far is that there are many tunable parameters and the time to train is quite long. What's weird about the current models is that the accuracy fluctuates greatly for no apparent reason.

<h1>Libraries used</h1>
<ol>
  <li>tensorflow</li>
  <li>re</li>
</ol>

<h1>First idea</h1>
Use fitbit technology to track sleep, run it through a model, and try to wake the user up at an earlier and better time.
Current Idea: Make an RNN and run it on labeled sleep data.
Needs: Data, RNN, Fitbit API, Test suite?, etc.

<h1>Second idea</h1>
Run sales records in a specific domain into an RNN and try to analyze successful patterns. It's like mining the phone call records, but instead it might eventually be good enough to call and sell on its own. If not perhaps it can provide useful ways to improve, or what differences between two sales people exist.

<h1>Third idea</h1>
Force wake-up based on ML model guessing when force waking up will be successful.