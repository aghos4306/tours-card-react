## Tours-card project

setup state value, loading and tours in App.js file.
Removing the tour functionality: if all tours are removed from the list, set up another return where I display no tours left and fetch tours by clicking refresh btn. First I decide where I am going to set up this functionality. Tour sits in Tours component, Tours sit in App component. The refresh btn should be in the Tour component. But tours data is in App.js component. It makes sense to have the removeTour function in App.js file where tours data sit and prop drill this function all the way to Tour component through Tours component.
