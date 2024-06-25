
init:
	yarn create redwood-app app --typescript
	cd app && yarn install

mig-dev:
	yarn rw prisma migrate dev

prisma-studio:
	yarn rw prisma studio

# generate the CRUD
g-sc:
	yarn rw g scaffold ${model}

# Cell
g-cell:
	yarn rw g cell ${name}

d-cell:
	yarn rw d cell ${name}

# page
g-page:
	yarn rw g page ${name}

# layout
g-layout:
	yarn rw g layout ${name}

d-layout:
	yarn rw d layout ${name}

# component
g-comp:
	yarn rw g component ${name}
d-comp:
	yarn rw d component ${name}

# types
g-types:
	yarn rw g types

# storybook
sb:
	yarn rw storybook

set-auth:
	yarn rw setup auth dbAuth

g-auth:
	yarn rw g dbAuth
