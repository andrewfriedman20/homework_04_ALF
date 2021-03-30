# The White House Staff Quiz (homework #4)
Description:

This project is intended as a fun quiz for the newly-minted junior White House Staffer or simply a politics and government enthusiast. The user is presented with a series of questions to test their knowledge of key White House staffers, cabinet officers, and Executive Office of the President (EOP) operations. The user is only given 60 seconds, and is penalized with reduced time for every wrong answer. It should be noted that the answers are selected via multiple choice, but the verbosity of the queries admittedly makes reading them time-consuming.


Known Issues:

A glitch about which I am both aware and intent on remedying when I have a moment is the scoring and over-deduction of time. The scoring is currently determined by the number of seconds the user has left when they successfully complete the quiz. It will be updated to reflect point values -- independent of the time variable. The time variable is meant to be a cudgle (when seconds are docked for incorrect responses) and as an urgency-enhancer. When the timer hits zero, the game should be over. There is an issue at present that could result in a situation wherein a user could get the last question wrong, for example, and the time deduction would produce a negative time value. This can lead to a negative score. 

No one should ever leave a quiz OWING points. These problems will be fixed.

Technologies Used:
Multiple JavaScript files to operate the quiz. Resets, Quiz Questions, scoring and high-scores. This project makes use of a timer and, at the time of the assignment, was the first to use local storage. It also uses HTML5 and CSS, of course.

<p>
  <img src="https://github.com/andrewfriedman20/homework_04_ALF/blob/main/ScreenShotQUIZ.png"/>
</p>


[Link to Deployed Page](https://andrewfriedman20.github.io/homework_04_ALF/)


[Link to Project GitHub Repository](https://github.com/andrewfriedman20/homework_04_ALF)


Copyright 2021, Andrew Friedman. All Rights Reserved.

The above copyright notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
