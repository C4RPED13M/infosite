# Advertisement Images Directory

This directory contains images used for advertisements throughout the Canada Election 2025 Information Site.

## Image Requirements

- Images should be in JPG or PNG format
- **Vertical Ad Format**: 450px × 600px (3:4 aspect ratio)
- **Horizontal Ad Format**: 800px × 450px (16:9 aspect ratio)
- Keep file sizes under 200KB for optimal performance
- Use descriptive filenames (e.g., "voter-registration.jpg" rather than "ad1.jpg")

## Ad Categories

The ad system is set up to support different categories of advertisements:

- `info`: Information about voting, elections, districts
- `civic`: Voter registration, civic engagement
- `events`: Debates, town halls, campaign events
- `interactive`: Quizzes, polls, interactive content

## Adding New Images

1. Add your image file to this directory
2. Update the `adData.js` file in `src/data` with the new ad information:
   - Add a new entry to the `adLinks` array
   - Include `id`, `title`, `description`, `url`, and `imageUrl`
   - Note: The title and description are stored in the data but not displayed

## Clickable Images

All ad images are directly clickable and will redirect to the URL specified in the ad data. These images appear:
- In the sidebar of the home page
- In the sidebar of party profile pages 
- Under candidate images on candidate profile pages

## Placeholder Images

For development, you can place placeholder images in this directory with the following naming convention:
- `placeholder-ad.jpg` - Default ad placeholder
- `election-info.jpg` - Information about the election
- `register.jpg` - Voter registration
- `debates.jpg` - Election debates
- `quiz.jpg` - Political quiz
- `districts.jpg` - Electoral districts 