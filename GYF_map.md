# Greening Youth Foundation Custom Google Map

[Greening Youth Foundation](https://gyfoundation.org/) is a non-profit based in Atlanta, Georgia with a mission to "engage under-represented youth and young adults, while connecting them to the outdoors and careers in conservation". The photo that was selected to create the color palette for their custom map utilzed the earth tone colors found in their promotional post for their HBCU Internship Initiative (see below).

## Image for Color Palette
![GYF Custom Map](/GYF_Palette_Inspo.png)

## Final Custom Map
![GYF Custom Map](/GYF_Custom_Map2.png)

## Design Decision Summary
1.	Adjusted density

- Decreased density of landmarks
- Increased density of roads and labels

2.	Selected ‘Standard’ theme

3.	Selected ‘More Options” and edited features (color selections in chart below)

Feature type | Element type | Stylers
------------ |------------- | ---------
All	| Geometry/fill	| Color: Pink Swan (#DAE9D7)
All	| Labels / Text fill | Color: Baltic Sea (#2D2B35)       
All |	Labels / text outline |	Color: Willow Brook (#DAE9D7)
Landscape / Human-made | Geometry / Stroke |	Color: Pink Swan (#B9B2B5)
Landscape / Natural	|Geometry |	Color: Sand Dune (#81695E)
Landscape / Natural |	Geometry / Stroke |	Color: Pink Swan (#B9B2B5)
Points of interest |	Labels / Text |	Hidden      
Points of interest/ Park | Labels / Text fill |	Color: Baltic Sea (#2D2B35)
Points of interest/ Park |	Labels / Text outline |	Color: Pink Swan (#B9B2B5)
Road | 	Geometry |	Color: Sand Dune (#81695E)
Road | Labels / Text fill |	Color: Willow Brook (#DAE9D7) 
Road |	Labels / Text outline |	Color: Baltic Sea (#2D2B35)
Road / Highway |	Geometry |	Color: Sand Dune (#81695E)
Road / Highway |	Geometry / Stroke |	Color: Pink Swan (#B9B2B5)
Road / Highway |	Labels / Text fill |	Color: Baltic Sea (#2D2B35)      
Road / Highway |	Labels / Text outline |	Color: Pink Swan (#B9B2B5)
Transit |	Geometry/ Fill |	Color: Baltic Sea (#2D2B35)      
Transit |	Labels / Text fill |	Color: Baltic Sea (#2D2B35)      
Transit |	Labels / Text outline |	Color: Willow Brook (#DAE9D7)
Transit / Line |	Geometry / Fill |	Color: Baltic Sea (#2D2B35)      
Transit/ Line |	Labels / Text fill |	Color: Baltic Sea (#2D2B35)      
Transit/ Line |	Labels / Text outline |	Color: Pink Swan (#B9B2B5)
Water |	Geometry/ Fill |	Color: Pink Swan (#B9B2B5)
Water |	Text fill |	Color: Baltic Sea (#2D2B35)      
Water |	Text outline |	Color: Willow Brook (#DAE9D7)

## JSON Code
[
  {
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#dae9d7"
      }
    ]
  },
  {
    "elementType": "labels",
    "stylers": [
      {
        "visibility": "on"
      }
    ]
  },
  {
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#dae9d7"
      }
    ]
  },
  {
    "featureType": "administrative",
    "elementType": "labels.icon",
    "stylers": [
      {
        "color": "#dae9d7"
      }
    ]
  },
  {
    "featureType": "administrative",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "administrative",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "landscape.man_made",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "landscape.natural",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#81695e"
      }
    ]
  },
  {
    "featureType": "landscape.natural",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#81695e"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "labels.icon",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#dae9d7"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#81695e"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#81695e"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "transit",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "transit",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "transit",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "transit",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#dae9d7"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#b9b2b5"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2d2b35"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#dae9d7"
      }
    ]
  }
]
