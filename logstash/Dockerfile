FROM logstash:5

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-codec-json
RUN logstash-plugin install logstash-codec-json_lines
RUN logstash-plugin install logstash-codec-rubydebug
