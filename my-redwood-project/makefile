
init:
	yarn create redwood-app app --typescript
	cd app && yarn install

mig:
	yarn rw prisma migrate dev

# generate the CRUD
g-sc:
	yarn redwood generate scaffold ${model}

sb:
	yarn rw storybook