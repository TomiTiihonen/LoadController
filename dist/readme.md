# Installation and Getting Started

Please note - this software is early limited release and is not necessarily production ready - please see the disclaimer.

To get started you need to:
1. Download latest version of load-controller jar from this directory
2. Download gatling 3.2 from https://gatling.io/open-source/ (LoadController has only been tested with 3.2 version)
3. Create new empty directory e.g. load-controller
4. Save jar file into this directory
5. Extract the contents of gatling archive into load-controller directory
6. In terminal run `java -jar load-controller-1.3.2.3.jar server`
7. In browser (LoadController has only been tested with Chrome browser) open http://localhost:8080

Note: After installation the directory structure should be something like this:
```
├── gatling-charts-highcharts-bundle-3.2.0
│   ├── LICENSE
│   ├── bin
│   ├── ...
├── scenarios
│   ├── ...
├── load-controller-1.3.2.3.jar
```
## Bugs and Feedback
If you find a bug or have feedback on usability or suggestions, please raise at https://github.com/TomiTiihonen/LoadController/issues

## Disclaimer
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
