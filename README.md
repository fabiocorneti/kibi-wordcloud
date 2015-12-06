# Kibi Word Cloud

## Development

- Clone the repository at the same level of a Kibana > 4.2 clone
- If needed, switch to the same node version as Kibana using nvm 
  (e.g. `nvm use 0.12`)
- Install dependencies with `npm install`
- Install the plugin to Kibana and start watching for changes by running 
  `npm start`

## Breaking changes with respect to the version embedded in Kibi 0.x

- The visualization name changed from `sindicetech_wordcloud` to 
  `kibi_wordcloud`
- The visualization parameter `showMeticsAtAllLevels` is now
  `showMetricsAtAllLevels`