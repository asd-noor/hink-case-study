![[Screenshot+2022-09-04+at+11.39.04+AM 1.png]]

# Streamlining Media Sharing for Events and Action Photography

- **Industry**: Social Media Platform
- **Region**: Canada
# 1. Summary and Overview
Hink, brainchild of Henric Ehrenblad, Limestone Lab Limited, is a platform designed to simplify the sharing and discovery of action photos. It addresses a common issue in action sports and event photography: missing photos taken by others. Hink makes it easy for users to access these images by allowing them to discover content based on location and events, without needing personal connections or invitations. The platform fosters a community around action sports and event photography, enabling users to capture, share, and relive dynamic experiences.
# 2. Technologies Used
- **Programming Languages**: Go, Dart, Javascript, HTML, CSS, Lua
- **Frameworks**: React, Flutter, Kong
- **Databases**: MySQL, ElasticSearch, Redis
- **Infrastructure**: GCP (GKE), AWS S3, AWS Lambda, Google Maps API, Stripe

# 3. Challenges and Solutions

| Challenge                                                                                                    | Solution                                                                                                                                                                                                                                                 |
| ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Client wanted people to upload photos tagged with location data so others can find it on the map.            | We integrated Google Maps API to get the best available map for Hink and used multipart upload to increase the upload speed for the content by utilising multiple concurrent connections to AWS S3, used Google Kubernetes Engine for high availability. |
| Client wanted to accept donations to the uploader of the content from whoever downloads it for full quality. | We integrated with Stripe Payment Gateway to accept donations via our platform.                                                                                                                                                                          |

# 4. Impact
After launching, Hink got huge attention from the hobbyist photographers as well as general mass.

![[Screenshot 2024-10-10 at 14.36.53.png]]

# 5. Team Involvement
- Developers: 2 Backend, 1 Mobile, 1 Frontend
- UI/UX: 1
As a project manager and tech lead of Hink, Asaduzzaman Noor ensured that client's requirements were satisfied after every release.

# 6. Core Features
- Share Photos tagged with a location and date.
- Create Collections of Photos and Videos for Events at any location.
- Earn money for uploads (via donation)
- Admin Dashboard to manage contents and users.

# 7. Development Timeline
Provide a high-level timeline of the project, including:
- Initial Discovery and Planning: 1 month
- Initial Design Phase: 2 weeks
- Initial Development: 6 months
- Initial Testing and Quality Assurance: 1 week
- Deployment & Post-launch Support: Perpetual

# 8. Screenshots

# 9. Testimonials (Client's Video Review)

# 10. Future Prospects
Currently, Hink is also maintained by us and looking ahead, it is hoped to continue.
# 11. Call-to-Action
