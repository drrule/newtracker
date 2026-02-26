# GeoGrid Rank Tracker - Vercel Ready

## 🚀 Deploy to Vercel

1. Download this entire folder
2. Go to https://vercel.com/new
3. Drag the folder onto the page
4. Click Deploy
5. Done!

## 📖 How to Use

Once deployed:
1. Enter your company/business name
2. Enter a keyword (e.g., "plumber", "restaurant", "lawyer")
3. Adjust grid settings if needed
4. Click "Start Scan"

The app currently runs with **demo/mock data** to show you how it works.

## 🔧 To Add Real Rank Checking

Edit `index.html` and change line with:
```javascript
provider: 'mock'
```

To one of:
- `'serpapi'` - Get free key at serpapi.com (100 searches/month free)
- `'google'` - Use Google Custom Search API
- `'backend'` - Run your own backend server (unlimited free)

See the API_CONFIG section in index.html for details.

## 💡 Features

✅ Interactive map with heatmap
✅ Customizable grid size (5×5, 7×7, 9×9)
✅ Adjustable spacing between points
✅ Scan history
✅ Average rank calculation
✅ Real-time progress tracking

Enjoy!
