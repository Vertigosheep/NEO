# NEO

Machine Learning Model on the Hazardous nature of near earth orbiting bodies.
Domain: Near-Earth Object (NEO) monitoring

# Title: Asteroid Hazard Prediction 

Asteroids are commonly characterized as diminutive rocky entities that orbit the sun. Certain asteroids have intersecting orbits with that of Earth, thereby posing a potential threat of collision with the planet. The impact of asteroids on Earth has the potential to result in the devastation of both human life and infrastructure. Therefore, it is imperative to develop a dependable model for predicting asteroid hazards that can estimate the likelihood of impact and its potential consequences. Asteroid Hazard Prediction hHelp scientists track asteroids that come close to earth by studying their size, speed and orbit and classifying them as non - hazardous or potentially hazardous.

# Type Of Problem: Binary Classification

The Goal will be to predict whether an asteroid is potentially hazardous(1) or non - hazardous(0) by implementing asteroid features such as size, speed and velocity as input to generate hazard label.

# Dataset Used: NASA NEO (Near-Earth Object) Dataset (Kaggle)

Feature Name
Description
id
Unique asteroid ID
name
Asteroid name
absolute_magnitude_h
Brightness (lower = brighter/larger)
estimated_diameter_min/max
Size range (km)
relative_velocity
Speed (km/h)
miss_distance
Distance from Earth
orbiting_body
Usually Earth
is_hazardous
Target label (True/False)

The dataset directly represents real astronomical observations:
Size (diameter) → Determines impact potential
Velocity → Determines impact energy
Distance (miss distance) → Determines risk level
Magnitude → Indicates size/visibility

The NASA NEO dataset provides physical attributes of asteroids with motion and spatial data which are highly relevant predictors for hazard classification. The data is cited from NASA - based sources and is well documented in tabular format. The dataset contains 33,125 NEOs in 1,657 pages which evades underfitting.The implementation of these techniques can enhance our comprehension and preparedness for prospective asteroid collisions, along with our capacity to effectively rank initiatives and distribute resources targeted at mitigating the gravity of such an impact. Furthermore, the utilization of these techniques can enhance our readiness for prospective collisions with asteroids.