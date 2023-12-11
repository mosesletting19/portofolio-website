#text-container, #image-container {
  flex: 1;
  overflow: hidden;
}

#text-container {
  background-color: #25242a;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 20px;
  
}
#container {
  display: flex;
  flex: 1;
  overflow: hidden;
}

#text-container {
  flex: 1;
  background-color: #25242a;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 20px;
}


#image-container img
 {
   border-radius:30% 70% 70% 30% / 30% 30% 70% 70%  ;
  width: 100%;
  height: 100%;
  object-fit: cover;
 
}

h1 {
  margin-bottom: 20px;
}

p {
  max-width: 400px;
  text-align: center;
}

button {
  padding: 10px 20px;
  font-size: 16px;
  background-color: #0088a9;
  color: white;
  border: none;
  border-radius: 50px;
  cursor: pointer;
}
h1,p, button
{
color: #fff;
}
button:hover {
  background-color: rgba(0,136, 169,0.7);
}