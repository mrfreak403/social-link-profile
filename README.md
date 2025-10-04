# Social Link Profile

A simple and elegant social link profile page. This project displays a user's profile information and social media links in a clean, modern interface.

## Features

- Displays user avatar, name, location, and bio.
- Lists social media links with corresponding icons.
- Responsive design for optimal viewing on different devices.

## Technologies Used

- HTML
- [Tailwind CSS](https://tailwindcss.com/)
- [Boxicons](https://boxicons.com/)

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/social-link-profile.git
   ```
2. Navigate to the project directory:
   ```bash
   cd social-link-profile
   ```
3. Open `index.html` in your web browser.

## Customization

You can customize the profile information by editing the `index.html` file or by modifying the `data.json` file and implementing a script to dynamically load the data.

### `data.json`

The `data.json` file contains the following structure:

```json
{
  "avatar": "https://i.pravatar.cc/150?u=a042581f4e29026704d",
  "name": "Jessica Randall",
  "location": "London, United Kingdom",
  "bio": "Front-end developer and avid reader.",
  "socialLinks": [
    {
      "name": "GitHub",
      "url": "https://github.com"
    },
    {
      "name": "LinkedIn",
      "url": "https://www.linkedin.com"
    },
    {
      "name": "Twitter",
      "url": "https://twitter.com"
    },
    {
      "name": "Instagram",
      "url": "https://www.instagram.com"
    }
  ]
}
```
