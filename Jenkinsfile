pipeline {
   agent any

   tools {
      // Install the Maven version configured as "M3" and add it to the path.
      maven "M3"
   }

   stages {
      buildApp( parameter1: null, { echo "This is the body function" } )
   }
}

