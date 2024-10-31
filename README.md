# TDSPROJECT1
Barcelona 100

This repository contains data about GitHub users in Barcelona with over 100 followers and their repositories.

## Files

1. `users.csv`: Contains information about 442 GitHub users in Barcelona with over 100 followers
2. `repositories.csv`: Contains information about 27480 public repositories from these users

How the data was scraped: Data was collected from GitHub using GitHub's REST API, targeting users in a specific location with a follower count greater than a set minimum and retrieving up to 500 recent repositories per user.


Most interesting finding: Users with high follower counts often work in well-established tech firms, and their repositories show significant activity in languages like  JavaScript, Python and TypeScript.


Recommendation for developers: Developers aiming to build their following on GitHub might benefit from consistently creating repositories in popular languages and updating them frequently to align with trends observed in high-follower accounts.

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 100+ followers
- Up to 500 most recently pushed repositories per user
