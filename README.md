# ![LOGO](logo.png) Soccer v3 Projections **flow**ground Connector

## Description

A generated **flow**ground connector for the Soccer v3 Projections API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/soccer-v3-projections/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:39+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Projected Player Game Stats by Competition (w/ DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `competition` - _required_ - An indication of a soccer competition/league. This value can be the CompetitionId or the Competition Key. Possible values include: <code>EPL</code>, <code>1</code>, <code>MLS</code>, <code>8</code>, etc.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.

### Projected Player Game Stats by Date (w/ DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.

### Projected Player Game Stats by Player (w/ DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-02-27</code>, <code>2017-09-01</code>.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>90026231</code>.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-soccer-v-3-projections-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
