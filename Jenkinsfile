pipeline
{
  agent any
  environment
  {
    ciudad = "Puebla"
    habitantes = 5000
    clima = "soleado"
  }
  stages
  {
    stage("info de mi ciudad")
    {
      steps
      {
        script
                {
                    echo "Mi ciudad se llama: ${ciudad}" 
                    echo "Tiene: ${habitantes}" 
                    echo " Y el clima es ${clima}"
                }
      }
    }
  stage("comando tipo BAT")
    {
      steps
      {
        bat 'ipconfig /flushdns'
      }
    }
  stage("usuario")
    {
      steps
      {
        script
                {
                  usuario = env.username
                    echo "el usuario que ejecuta la tarea es: ${usuario}"
                }
      }
    }
}
}
