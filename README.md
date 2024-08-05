# Web-Penetration-testing


## Google Dorking Terms for Pentesting

1. **intitle: site:**
   - Search for pages with a specific keyword in the title within a specified site.
   - Useful for finding targeted content on a particular website.

2. **filetype:**
   - Find specific file types (e.g., PDF, DOCX) on websites.
   - This can help locate sensitive documents or configurations.

3. **cache:**
   - View Google's cached version of a webpage to see its content at a specific time.
   - Handy for accessing pages that are down or have changed.

4. **allinurl:**
   - Search for pages where all the specified keywords are in the URL.
   - Useful for pinpointing specific directory or file structures.

5. **inurl:**
   - Find pages with a specific keyword in the URL.
   - Helps to locate pages with particular parameters or content types.

6. **allintitle:**
   - Search for pages where all specified keywords appear in the title.
   - Efficient for finding relevant pages focused on specific topics.

7. **inanchor:**
   - Locate pages with a specific keyword in the anchor text of links.
   - Useful for understanding link context and finding backlinks.

8. **allinanchor:**
   - Find pages with all specified keywords in the anchor text of links.
   - Helps in identifying pages with specific linking phrases.

9. **link:**
   - Discover pages that link to a specific URL.
   - This can reveal backlink sources and potential influencers.

10. **related:**
    - Identify websites related to a specified site.
    - Useful for finding similar or competitor sites.

11. **info:**
    - Retrieve information about a specific webpage, including cache, similar pages, and more.
    - Offers a quick overview of a page's details.

12. **location:**
    - Find results based on a specified geographical location.
    - Useful for geo-targeted searches and local information.

## Information from FTP Search Engines

File Transfer Protocol (FTP) search engines are used to search for files located on FTP servers; these files may hold valuable information about the target organization. Many industries, institutions, companies, and universities use FTP servers to keep large file archives and other software that are shared among their employees. FTP search engines provide information about critical files and directories, including valuable information such as business strategies, tax documents, employees' personal records, financial records, licensed software, and other confidential information. Here, we will use the NAPALM FTP indexer FTP search engine to extract critical FTP information about the target organization.

- Go to [Search FTPs](https://www.searchftps.net/)
- Search for the target organization site

You can also use [Freeware WB](http://www.freewarewb.com)

## Find the Company's Domains and Sub-domains using Netcraft
1. **Go to [Netcraft](https://www.netcraft.com)**.
2. **Access the Site Report Tool**:
   - Navigate to [Netcraft Site Report](https://sitereport.netcraft.com/).
3. **Search for the Primary Domain**:
   - Enter `example.com` in the search bar and generate the report.
4. **Review the Site Report**:
   - Note the hosting provider, IP addresses, and other technical information.
   - Identify any listed sub-domains and related domains.
5. **Conduct Additional Searches**:
   - Use Netcraft's search function to find more domains related to the company.
