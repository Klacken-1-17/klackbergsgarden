# Hotel Klackbergsgården Website

This is the website for Hotel Klackbergsgården, located in Norberg, Sweden. It provides information about the hotel, rooms, activities, and allows visitors to make bookings.

## Pages

- Home: Overview of the hotel and featured content
- Rooms: Descriptions and photos of the available room types 
- Activities: Information about activities and attractions in the surrounding area
- Contact: Contact information and a form to send messages to the hotel

## Technologies Used

- Jekyll static site generator
- HTML
- CSS
- JavaScript
- Bootstrap front-end framework

## Season Configuration

The website supports seasonal content through a season parameter in `_config.yml`. This allows for different images to be displayed based on the season:

- Set `season: winter` for winter-themed images
- Set `season: summer` for summer-themed images

Images should be organized in the following structure:

images/
├── winter/
│ └── [image files]
└── summer/
  └── [image files]
## Deploying 

This site is deployed on GitHub Pages. Any changes pushed to the `main` branch will be automatically published.

To run locally:

1. Install Jekyll and dependencies:
   ```
   gem install jekyll bundler
   bundle install
   ```

2. Start the Jekyll development server:
   ```
   bundle exec jekyll serve --config _config.yml,_config_dev.yml
   ```

3. Open http://localhost:4000/klackbergsgarden in your browser to preview the site.

## Domain

The custom domain for this site is configured in the `CNAME` file.

## Contributing

If you notice any issues or have suggestions for improving the site, please open an issue or submit a pull request on the GitHub repository.

## Contact

For questions about the hotel or bookings, please use the contact information provided on the website.