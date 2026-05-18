# load-testing-with-jmeter

Pre-requsite:
- Install java & setup JAVA_HOME, it's path on enviornment variables.
- Install apache JMeter & setup JMETER_HOME, it's path on enviornment variables.

To run jmx file on JMeter tool:
- Open command prompt.
- Write jmeter.
- As JMeter tool open -> go to file -> click on open -> open your jmx file.
- Click on Start button (green color).

To Generate Report:
- Go to your JMeter file location
- Open cmd git bash
- Write on cmd : jmeter -n -t yourFile.jmx -l yourFile.csv -e -o Reports
