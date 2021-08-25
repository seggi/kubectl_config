Helm Chart Structure

Directory structure:

mychart/
    Chart.yml
    values.yml
    Charts/
    templates/
    ...

Top level mychart folder name
Chart.yml => meta info "chart"
values.yml => templates value files
charts => folder chart dependencies
templates folder => current template files

# Execution
helm install <chartname>
helm upgrade <version >
helm rolled <back to previous one>