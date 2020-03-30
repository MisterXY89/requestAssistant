
# Request Assistant

Avoid your requests from being blocked by using random *UserAgents* and *languages* for each request. <br>
**As an additional measure use random time intervals between each request.**

## Usage
```python
import requests
from requestAssistant import RequestHeaderGenerator

url = "https://yourdomain.com"
rhg = RequestHeaderGenerator()
randomHeader = rhg.getRandomRequestHeader()


requests.get(url, headers=randomHeader)
```

## Requirements
`pip3 install numpy`


## Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to the LICENSE or https://unlicense.org
