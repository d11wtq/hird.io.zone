# Zone configuration for hird.io

This is the main DNS configuration for my domain hird.io.

It is managed through a currently closed-source infrastructure-as-code project
of mine and deployed with:

    curl -XPUT --data-binary @zone.yml \
      -H 'Content-Type: text/yaml' \
      http://service-name/stacks/hird-io-zone
