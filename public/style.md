* {
  font-family: sans-serif;
  box-sizing: border-box;
}

img{
  width: 600px;
  height: 300px;
  object-fit: cover;
}


.item {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  margin: 64px 0 32px 0;
  align-items: center;
}

.item-button {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  margin: 0;
  align-self: center;
}

.sidebar {
  display: flex;
  flex-wrap: nowrap;
  flex-direction: column;
  align-self: flex-start;
  position: relative;
  margin-left: 48px;
  width: 80px;
  margin-right: 48px;
}

.sidebar-title {
  margin-bottom: 16px;
  font-size: 24px;
}

.info {
  list-style: none;
  text-align: center;
  border-bottom: 1px solid rgb(189, 186, 186);
  padding: 4px;
  width: 80px;
}

.tagline {
  text-align: center;
  font-size: 4rem;
}

.tagline-edit {
  font-size: 3rem;
}

.ui-btn {
  font-size: inherit;
  margin: 0;
  padding: 0 12px;
  border-bottom: 2px solid rgb(230, 116, 116);
}

h4,
h1,
h1 > .title {
  font-size: 64px;
  padding: 0;
  margin: 16px 0 0 0;
  font-weight: lighter;
}
.camp-name {
  font-size: 64px;
}

h3 {
  font-size: 32px;
  padding: 0;
  margin: 16px 0 0 0;
  font-weight: lighter;
}

img {
  width: 500px;
}

/*.title{*/
/*    margin-bottom: 24px;*/
/*}*/

a {
  font-size: 24px;
  font-weight: lighter;
  margin: 16px 0 0 0;
  padding: 0;
  color: black;
  text-decoration: none;
}

a:visited {
  color: black;
}

a:hover {
  color: rgb(230, 116, 116);
}

input {
  margin: 32px 16px 32px 0;
  border: none;
  font-size: 16px;
  outline: none;
}

button,
.btn {
  border: none;
  color: black;
  font-size: 16px;
  transition: transform ease-in-out 0.1s, color ease-in-out 0.1s;
}

button:hover,
.btn:hover {
  color: rgb(230, 116, 116);
  border: inherit;
  transform: scale(1.3);
}

.button,
#back-button {
  display: block;
  width: max-content;
  text-align: center;
  margin: 0 auto;
  color: black;
}

form {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.input {
  font-size: 32px;
  margin: 0 auto;
  text-align: center;
  margin-bottom: 16px;
  width: 320px;
  border-bottom: 1px solid rgba(204, 0, 0, 0.2);
}

input + button {
  margin-top: 16px;
  /*margin-bottom: 16px;*/
}

nav {
  padding: 0 24px;
}
/*nav > h1{*/
/*    display:inline;*/
/*    font-size:24px;*/
/*    text-align:left;*/
/*}*/

/*nav > a {*/
/*font-size: 16px;*/
/* align-self:flex-end;  */
/*}*/

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid rgba(204, 0, 0, 0.2);
}

.navbar-links {
  display: flex;
  margin-right: 24px;
}

div > a {
  padding: 0 8px;
}

.comments-wrapper {
  padding: 8px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 500px;
  align-items: baseline;
  font-weight: 200;
}

.comments {
  font-size: larger;
  display: inline;
  margin: 16px;
}

.comment-timestamp {
  margin-left: 48px;
}

.camp-info {
  position: relative;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 500px;
  padding-top: 16px;
  margin-bottom: 16px;
}

.camp-description {
  display: inline-block;
  margin: 0;
  font-size: 400;
}

.price {
  font-weight: 400;
  margin: 0;
  align-self: flex-end;
}

#delete-btn{
  background-color: rgba(109, 46, 46, 0.048);
  margin-top: 24px;
  padding: 12 0 0 0;
  border-bottom: none;
  font-weight: lighter;
}

#delete-btn:hover{
  color: crimson;
}