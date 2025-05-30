"Test8 CI/CD"


.gitmodules
git submodule sync --recursive
git submodule update --init --recursive

run docker and then
docker-compose up --build


git submodule update --remote
cd studentmanagement-clone
git merge origin/main --allow-unrelated-histories
