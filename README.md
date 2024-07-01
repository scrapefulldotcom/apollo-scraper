## Apollo Scraper

Want to supercharge your lead generation? Apollo.io gives you 10k email credits monthly. That's awesome, right? But here's the catch. Their export limits are tight. Free plan? Just 120 exports yearly.

Our [Apollo Scraper](https://apify.com/scrapefull/apollo-scraper) changes the game. It bypasses those export limits. You can grab up to 10k emails monthly or 120k yearly, regardless of your plan.

And it's not just emails. You get it all - phone numbers, job titles, the works. All the details from your Apollo leads search, in easy to export formats and ready to be imported into your CRM or sales outreach tools.

## Why Choose the Apollo Scraper?

Manually gathering leads from Apollo.io can be tedious and limited. Our scraper eliminates those barriers by providing:

- **Automation:** Bypass the grind of manual extraction and let the scraper do the heavy lifting for you.
- **Data Accuracy:** Get access to verified email addresses and phone numbers, boosting your outreach success rate.
- **Customization:** Tailor your search based on specific criteria like industry, location, job title, and more.
- **Scalability:** Scrape thousands of leads quickly and efficiently, fueling your sales pipeline with ease.

## How It Works

1. **Define your search parameters:** Specify the criteria for your ideal leads directly within the actor's input.
2. **Launch the scraper:** Sit back and relax as the scraper automatically gathers detailed lead information from Apollo.io.
3. **Access your data:** Download the scraped data in various formats, ready to be integrated into your CRM or sales outreach tools.

## How to Authenticate

### Using Cookies

This method is recommended since it uses the same session cookies as the one you use.

1. Install [Editthiscookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension.
2. Login to your Apollo.io account.
3. After logging in, click the extension icon, then the "Export" icon (5th from left in the extension menu).
4. When you click it, it'll copy the cookies to your clipboard, then paste that in the "Cookie" field in the actor's input.

### Using Email and Password

1. Enter your Apollo.io email and password in the "Email" and "Password" fields, respectively in the actor's input.

## Apollo.io Scraped Data Fields

| Field Name                                                                        | Data Structure               | Description                                                                                   |
| --------------------------------------------------------------------------------- | :--------------------------- | :-------------------------------------------------------------------------------------------- |
| **Contact ID**                                                                    | String                       | Unique identifier for the contact                                                             |
| **First Name**                                                                    | String                       | First name of the contact                                                                     |
| **Last Name**                                                                     | String                       | Last name of the contact                                                                      |
| **Full Name**                                                                     | String                       | Full name of the contact                                                                      |
| **LinkedIn URL**                                                                  | String (URL), nullable       | URL of the contact's LinkedIn profile                                                         |
| **Job Title**                                                                     | String                       | Job title of the contact                                                                      |
| **Email Status**                                                                  | String                       | Status of the contact's email address (e.g., verified, unverified)                            |
| **Photo URL**                                                                     | String (URL), nullable       | URL of the contact's profile photo                                                            |
| **Twitter URL**                                                                   | String (URL), nullable       | URL of the contact's Twitter profile                                                          |
| **GitHub URL**                                                                    | String (URL), nullable       | URL of the contact's GitHub profile                                                           |
| **Facebook URL**                                                                  | String (URL), nullable       | URL of the contact's Facebook profile                                                         |
| **Extrapolated Email Confidence**                                                 | Integer, nullable            | Confidence level of the extrapolated email address (if applicable)                            |
| **Professional Headline**                                                         | String                       | Professional headline of the contact                                                          |
| **Email Address**                                                                 | String                       | Email address of the contact                                                                  |
| **Organization ID**                                                               | String                       | Unique identifier for the contact's organization                                              |
| **Employment History**                                                            | Array of Objects             | Employment history of the contact                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;**Employment History Entry ID**                           | String                       | Unique identifier for the employment history entry                                            |
| &nbsp;&nbsp;&nbsp;&nbsp;**Created At**                                            | String (Date-Time), nullable | Timestamp of when the employment history entry was created                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;**Is Current Role?**                                      | Boolean                      | Whether the contact is currently employed in this role                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;**Degree**                                                | String, nullable             | Degree earned during this employment (if applicable)                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;**Role Description**                                      | String, nullable             | Description of the contact's role and responsibilities                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;**Emails**                                                | Array of Strings             | List of email addresses associated with this employment                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;**End Date**                                              | String (Date), nullable      | End date of the employment                                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;**Grade Level**                                           | String, nullable             | Grade level during this employment (if applicable)                                            |
| &nbsp;&nbsp;&nbsp;&nbsp;**Employment Type**                                       | String, nullable             | Type of employment (e.g., full-time, part-time, internship)                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;**Major**                                                 | String, nullable             | Major studied during this employment (if applicable)                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;**Organization ID**                                       | String, nullable             | Unique identifier for the organization                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;**Organization Name**                                     | String                       | Name of the organization                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;**Raw Address**                                           | String, nullable             | Raw address of the organization                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;**Start Date**                                            | String (Date)                | Start date of the employment                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;**Job Title**                                             | String                       | Job title during this employment                                                              |
| &nbsp;&nbsp;&nbsp;&nbsp;**Updated At**                                            | String (Date-Time), nullable | Timestamp of when the employment history entry was last updated                               |
| **State**                                                                         | String                       | State where the contact is located                                                            |
| **City**                                                                          | String                       | City where the contact is located                                                             |
| **Country**                                                                       | String                       | Country where the contact is located                                                          |
| **Organization**                                                                  | Object                       | Information about the contact's organization                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;**Organization ID**                                       | String                       | Unique identifier for the organization                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;**Organization Name**                                     | String                       | Name of the organization                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;**Website URL**                                           | String (URL), nullable       | URL of the organization's website                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;**Blog URL**                                              | String (URL), nullable       | URL of the organization's blog                                                                |
| &nbsp;&nbsp;&nbsp;&nbsp;**AngelList URL**                                         | String (URL), nullable       | URL of the organization's AngelList profile                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;**LinkedIn URL**                                          | String (URL), nullable       | URL of the organization's LinkedIn profile                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;**Twitter URL**                                           | String (URL), nullable       | URL of the organization's Twitter profile                                                     |
| &nbsp;&nbsp;&nbsp;&nbsp;**Facebook URL**                                          | String (URL), nullable       | URL of the organization's Facebook page                                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;**Primary Phone**                                         | Object                       | Primary phone number of the organization                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Phone Number**                  | String                       | Phone number                                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Phone Number Source**           | String                       | Source of the phone number                                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Sanitized Phone Number**        | String                       | Sanitized phone number                                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;**Languages Spoken**                                      | Array of Strings             | Languages spoken at the organization                                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;**Alexa Ranking**                                         | Integer, nullable            | Alexa ranking of the organization's website                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;**Phone Number**                                          | String                       | Phone number of the organization                                                              |
| &nbsp;&nbsp;&nbsp;&nbsp;**LinkedIn UID**                                          | String                       | Unique identifier for the organization's LinkedIn profile                                     |
| &nbsp;&nbsp;&nbsp;&nbsp;**Founded Year**                                          | Integer, nullable            | Year the organization was founded                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;**Publicly Traded Symbol**                                | String, nullable             | Stock symbol of the organization (if publicly traded)                                         |
| &nbsp;&nbsp;&nbsp;&nbsp;**Publicly Traded Exchange**                              | String, nullable             | Stock exchange where the organization is listed (if publicly traded)                          |
| &nbsp;&nbsp;&nbsp;&nbsp;**Logo URL**                                              | String (URL), nullable       | URL of the organization's logo                                                                |
| &nbsp;&nbsp;&nbsp;&nbsp;**Crunchbase URL**                                        | String (URL), nullable       | URL of the organization's Crunchbase profile                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;**Primary Domain**                                        | String                       | Primary domain name of the organization                                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;**Sanitized Phone Number**                                | String                       | Sanitized phone number of the organization                                                    |
| **Is Likely to Engage?**                                                          | Boolean                      | Whether the contact is likely to engage with outreach                                         |
| **Departments**                                                                   | Array of Strings             | Departments the contact belongs to                                                            |
| **Subdepartments**                                                                | Array of Strings             | Subdepartments the contact belongs to                                                         |
| **Seniority Level**                                                               | String                       | Seniority level of the contact (e.g., c-suite, vp, director, manager, individual contributor) |
| **Job Functions**                                                                 | Array of Strings             | Job functions of the contact (e.g., sales, marketing, engineering)                            |
| **Phone Numbers**                                                                 | Array of Objects             | List of phone numbers associated with the contact                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;**Raw Phone Number**                                      | String                       | Raw phone number                                                                              |
| &nbsp;&nbsp;&nbsp;&nbsp;**Sanitized Phone Number**                                | String                       | Sanitized phone number                                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;**Phone Number Type**                                     | String                       | Type of phone number (e.g., work, mobile, home)                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;**Position in List**                                      | Integer                      | Position of the phone number in the list                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;**Phone Number Status**                                   | String                       | Status of the phone number (e.g., no_status, valid, invalid)                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;**Do Not Call (DNC) Status**                              | String, nullable             | Do Not Call (DNC) status of the phone number                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;**Other DNC Info**                                        | String, nullable             | Other information about the DNC status                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;**Dialer Flags**                                          | Object                       | Flags related to dialing the phone number                                                     |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Country Name**                  | String                       | Country of the phone number                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Dialing Enabled for Country?**  | Boolean                      | Whether dialing to this country is enabled                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**High-Risk Calling Enabled?**    | Boolean                      | Whether high-risk calling to this number is enabled                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Potentially High-Risk Number?** | Boolean                      | Whether the phone number is potentially high-risk                                             |
| **Intent Strength**                                                               | String, nullable             | Strength of the contact's intent to purchase (if applicable)                                  |
| **Show Intent Data?**                                                             | Boolean                      | Whether to show intent data for this contact                                                  |
| **... (Refer to the JSON structure for the complete list of fields) ...**         |                              |                                                                                               |

## Best Practices

To optimize your use of the Apollo Scraper, consider the following best practices:

1. **Implement appropriate delays:** Set a delay between 2 to 50 seconds between requests.

2. **Limit daily scraping volume:** Restrict your scraping to no more than 1,000 records per day to maintain a sustainable data collection rate.

3. **Maintain consistent proxy location:** Choose residential proxy from the same country where you usually log into Apollo to have consistent access patterns.

4. **Prefer cookie-based authentication:** Whenever possible, use cookies for authentication rather than login credentials. This method is generally more secure and less likely to trigger account security measures.

5. **Avoid simultaneous scraping:** Do not run multiple scraping instances with the same Apollo account concurrently, as this may be flagged as suspicious activity.

6. **Monitor your email credits:** If the scraper stops unexpectedly, check your Apollo settings to ensure you haven't exhausted your monthly email credits. Maintaining sufficient credits is crucial for uninterrupted scraping.

By following these best practices, you can ensure efficient and responsible use of the Apollo Scraper while minimizing the risk of account restrictions or service interruptions.

## Flexible Data Export Options

Download your scraped data in various formats:

- JSON
- CSV
- Excel
- XML
- HTML Table
- RSS
- JSONL

## Integrate for Sales Outreach

Seamlessly integrate the scraped data with:

- **CRM Systems:** Populate your CRM with accurate lead information, enriching your existing database and improving sales efficiency.
- **Sales Automation Tools:** Automate your outreach campaigns by directly importing leads and their contact details.
- **Email Marketing Platforms:** Segment and target your email campaigns effectively based on scraped lead data.

## Unlock Growth with Apollo Leads Scraper

Stop relying on outdated methods. Leverage the power of the Apollo Scraper to:

- **Identify Ideal Prospects:** Focus your outreach efforts on leads that perfectly match your target audience.
- **Boost Conversion Rates:** Reach the right decision-makers with verified contact information, increasing your chances of closing deals.
- **Gain a Competitive Advantage:** Stay ahead of the curve by consistently filling your pipeline with high-quality leads.

## Help & Support

Contact us at help@scrapefull.com.
