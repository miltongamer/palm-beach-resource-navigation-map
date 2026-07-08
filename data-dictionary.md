# Data Dictionary

This file explains the fields used in `resources.csv`.

| Field | Description | Example |
|---|---|---|
| id | Unique numeric identifier for each resource. | 1 |
| name | Name of organization, program, or resource. | Example Shelter Program |
| category | Main resource category. | Housing |
| subcategory | More specific service type. | Emergency Shelter |
| population_served | Primary groups served. | Veterans, adults, families |
| description | Plain-language summary of what the resource does. | Provides emergency shelter and case management. |
| phone | Main phone number. | 555-555-5555 |
| email | Main public email, if available. | intake@example.org |
| website | Public website. | https://example.org |
| address | Physical address, if appropriate. | 123 Main Street |
| city | City. | West Palm Beach |
| state | State abbreviation. | FL |
| zip | ZIP code. | 33401 |
| service_area | Geographic area served. | Palm Beach County |
| eligibility_notes | Requirements, restrictions, or documentation needed. | Must be Palm Beach County resident. |
| referral_process | How someone accesses the service. | Call intake line Monday-Friday. |
| hours | Hours of operation. | Monday-Friday 9am-5pm |
| cost | Cost or payment information. | Free, sliding scale, insurance, varies |
| transportation_available | Whether the organization provides or helps with transportation. | Yes, No, Unknown, Limited |
| source_url | Link to the source used for the information. | https://example.org/services |
| last_verified | Date the information was last checked. | 2026-07-07 |
| verification_status | Status of verification. | Verified, Partially verified, Needs verification |
| confidence_level | Confidence in the accuracy of the listing. | High, Medium, Low |
| notes | Internal or public notes for context. | Call before referral; hours may change. |

## Recommended categories

- Housing
- Homeless Services
- Veteran Services
- Behavioral Health
- Substance Use Treatment
- Crisis Support
- Food Support
- Hygiene Services
- Legal Aid
- Transportation
- Financial Assistance
- Reentry Support
- Family Services
- Medical Care
- Benefits Navigation
- Employment Support

## Recommended verification cadence

- Crisis resources: every 30 days
- Shelter and housing resources: every 30–60 days
- Food/hygiene resources: every 60 days
- Legal and benefits resources: every 90 days
- General nonprofit resources: every 90–180 days
