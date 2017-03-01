def venv(command)
    sh "source venv/bin/activate && #{command}"
end

desc "Build venv from requirements.txt"
task :build_venv do
    sh "pyvenv venv"
    venv "pip install --upgrade pip"
    venv "pip install -r requirements.txt"
end
