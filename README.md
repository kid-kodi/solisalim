"scp -r ./build/\* fatihoune@196.70.254.249:/var/www/telmed/html" mongo --port
27017 -u "admin" -p "6692" --authenticationDatabase "admin"

use telmed

db.createUser({ user: "solisalimAdmin", pwd: "6692", roles: [{ role: "dbAdmin",
db: "solisalim" }, { role: "readWrite", db: "solisalim" } ]})
MONGODB_URL_PROXY=mongodb://telmedAdmin:6692@localhost:27017/telmed

# Front end

# Back end

# image de couverture

Todo

- Authentification system

  1. Login page ok
  2. Register page ok
  3. Forgot password page.
  4. Code checking page.
  5. Reset password page.

- Post management system.

  1. List of posts page.
  2. Post form page.
  3. Post details page.

- Video management system.

  1. List of videos page.
  2. Video form page.
  3. Video details page.

- Music management system.

  1. List of music page.
  2. Music form page.
  3. Music details page.

- Book management system.

  1. List of book page.
  2. Book form page.
  3. Book details page.

- Profile management system.

  1. Profile page.
  2. Edit profile page.
  3. Edit avatar page.

- Layouts
  1. Shell layout. OK
  2. App layout.
  3. Page layout.

View props errors......

// Deprecated Prop Types get ColorPropType(): $FlowFixMe { return
require("deprecated-react-native-prop-types").ColorPropType }, get
EdgeInsetsPropType(): $FlowFixMe { return
require("deprecated-react-native-prop-types").EdgeInsetsPropType }, get
PointPropType(): $FlowFixMe { return
require("deprecated-react-native-prop-types").PointPropType }, get
ViewPropTypes(): $FlowFixMe { return
require("deprecated-react-native-prop-types").ViewPropTypes },

List des articles.

- PostSearch.js
- PostTags.js
- PostList.js
- PostItem.js

PostScreen.js
