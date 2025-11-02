# Countdown Page

This is a simple "Coming Soon" countdown page.

## Deployment on Render

1. Set your Render API key:

```bash
export RENDER_API_KEY=your_render_api_key

2. Trigger deployment:



curl -X POST "https://api.render.com/v1/services/<YOUR_SERVICE_ID>/deploys" \
-H "Authorization: Bearer $RENDER_API_KEY" \
-H "Content-Type: application/json" \
-d '{}'

Customization

Update the launch date in index.html by changing the countdown target.

You can replace the background and text styles to match your branding.


License

This project is open-source and available under the MIT License.
